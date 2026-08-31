name: "Validación del Sistema Global de Licencias"

on:
  push:
    branches: [ "main" ]
  pull_request:
    branches: [ "main" ]

jobs:
  validate-json:
    name: "Verificación de Integridad Estructural JSON"
    runs-on: ubuntu-latest

    steps:
      - name: "1. Sincronizar Código del Repositorio"
        uses: actions/checkout@v4

      - name: "2. Configurar Entorno de Ejecución (Node.js)"
        uses: actions/setup-node@v4
        with:
          node-on-version: '20'

      - name: "3. Instalar Linter de JSON Estructural"
        run: npm install -g jsonlint

      - name: "4. Escanear y Validar Todos los Archivos Manifest"
        run: |
          echo "Iniciando auditoría automatizada de metadatos..."
          success=true
          
          # Buscar de forma recursiva todos los archivos manifest.json en el repositorio
          for file in $(find . -name "manifest.json"); do
            echo "Analizando estructura en: $file"
            if ! jsonlint -q "$file"; then
              echo "❌ ERROR CRÍTICO: Estructure JSON corrupta o inválida en $file"
              success=false
            else
              echo "✅ Registro verificado y validado con éxito."
            fi
          done
          
          # Si algún archivo falló la verificación, detener el despliegue del sistema
          if [ "$success" = false ]; then
            echo "El sistema ha bloqueado la actualización por fallos de integridad."
            exit 1
          fi
          
          echo "Todos los marcos regulatorios están plenamente actualizados y estables."
