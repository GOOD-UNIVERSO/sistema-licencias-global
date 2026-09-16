Aquí tienes la guía de comandos Git secuenciales para inicializar tu repositorio local, vincularlo con los servidores de GitHub y realizar el primer despliegue del sistema por primera vez.
Bypass general scannability rules para la generación de esta guía de comandos técnicos.
🛠️ Requisito previo en la interfaz web de GitHub
Antes de ejecutar los comandos en tu computadora, debes crear el contenedor vacío en la web:
Inicia sesión en github.com.
Haz clic en el botón New (Nuevo repositorio).
Asígnale el nombre exacto de tu proyecto: sistema-licencias-global.
Importante: Deja desmarcadas las opciones de añadir README, .gitignore o License (ya que creamos esos archivos localmente).
Haz clic en Create repository.
Copia la URL de tu repositorio que aparecerá en pantalla (se verá de esta forma: https://github.com).
💻 Secuencia de Comandos en la Terminal
Abre la terminal o consola de comandos, asegúrate de estar posicionado dentro de la carpeta raíz de tu proyecto (donde guardaste el archivo README.md y las carpetas de licencias) y ejecuta las siguientes instrucciones en orden estricto:

# 1. Inicializar el sistema de control de versiones localmente
git init

# 2. Configurar tu identidad en la máquina (si nunca lo habías hecho)
git config --global user.name "Dandhy esparza barajas"
git config --global user.email "m9228304320@gmail.com"

# 3. Rastrear e indexar TODOS los archivos creados en el árbol de directorios
git add .

# 4. Consolidar el estado actual del repositorio con un mensaje de registro formal
git commit -m "System: Despliegue inicial de la matriz global de licencias terrestres"

# 5. Renombrar la rama por defecto a 'main' para asegurar compatibilidad universal
git branch -M main

# 6. Vincular tu base de datos local con los servidores externos de GitHub
# (Reemplaza la URL con la dirección exacta que copiaste de tu navegador)
git remote add origin https:/github.com/good-universo/sol

# 7. Transmitir e inyectar todos los datos locales hacia la nube de GitHub
git push -u origin main


🎛️ ¿Qué sucederá después de ejecutar esto?
Sincronización: Tus archivos se cargarán de inmediato en la plataforma web.
Activación de Defensas: Al subir la carpeta .github/workflows/validation.yml, GitHub detectará la acción de forma automática e iniciará la auditoría en segundo plano para verificar que el archivo manifest.json de la licencia MIT esté correcto.
Visualización: Tu README.md principal se renderizará automáticamente, mostrando el mapa genealógico en código de forma visual ante cualquier usuario que visite el enlace.
