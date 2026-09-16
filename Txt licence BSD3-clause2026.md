Aquí tienes el par de archivos oficiales correspondientes a la licencia BSD de 3 cláusulas (BSD-3-Clause) para la sección académica permisiva de tu repositorio.
Debes ubicar estos dos archivos exactamente dentro de la ruta: SOFTWARE-LICENSES/permissive/BSD-3-Clause/.
Bypass general scannability rules para la generación de estos documentos técnicos y legales.
1. El Texto Legal Exacto: license.txt
Este es el texto jurídico oficial de la licencia BSD modificada (3-Clause). Mantiene la extrema libertad del código, pero añade la tercera cláusula que prohíbe de forma explícita usar el nombre de la organización o de sus contribuyentes para respaldar o promocionar productos derivados sin un permiso previo por escrito.

BSD 3-Clause License

Copyright (c) 2026 Sistema Global de Licencias Terrestres
All rights reserved.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met:

1. Redistributions of source code must retain the above copyright notice, this
   list of conditions and the following disclaimer.

2. Redistributions in binary form must reproduce the above copyright notice,
   this list of conditions and the following disclaimer in the documentation
   and/or other materials provided with the distribution.

3. Neither the name of the copyright holder nor the names of its
   contributors may be used to endorse or promote products derived from
   this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS"
AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE
IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE
FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL
DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR
SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER
CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY,
OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING FROM, OUT OF OR IN
CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.


2. La Ficha Técnica Normalizada: manifest.json
Este archivo traduce las condiciones académicas y las restricciones de promoción comercial de la BSD-3-Clause a variables lógicas booleanas para tu sistema de validación.

{
  "$schema": "https://json-schema.org",
  "identificador_sistema": {
    "id_spdx": "BSD-3-Clause",
    "nombre_oficial": "BSD 3-Clause \"New\" or \"Modified\" License",
    "version": "3.0",
    "estado_vigencia": "ACTIVO"
  },
  "genealogia": {
    "licencia_padre": "BSD-4-Clause",
    "ano_lanzamiento": 1999,
    "entidad_emisora": "Regents of the University of California",
    "bifurcaciones_o_descendientes": [
      "BSD-2-Clause"
    ]
  },
  "matriz_de_reglas": {
    "permisos": {
      "uso_comercial": true,
      "modificacion_codigo": true,
      "distribucion_copias": true,
      "sublicenciar": true,
      "uso_en_red_cloud": true
    },
    "condiciones": {
      "incluir_aviso_copyright": true,
      "incluir_texto_licencia": true,
      "divulgar_codigo_fuente": false,
      "rastrear_cambios_realizados": false
    },
    "limitaciones": {
      "garantia_legal_incluida": false,
      "responsabilidad_danos": false,
      "uso_marcas_comerciales": true
    }
  },
  "metadatos_sincronizacion": {
    "es_compatible_con_gpl_v3": true,
    "tipo_codigo_fuente": "Abierto / Permisivo Académico",
    "ultima_verificacion_terrestre": "2026-08-28"
  }
}


