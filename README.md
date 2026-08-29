# sistema-licencias-global
Taxonomía completa de licencias de software y contenido: genealogía, compatibilidad, fichas técnicas y mapeos visuales
ARCHIVO GLOBAL DE REGÍMENES DE LICENCIAMIENTO HUMANO
Índice Taxonómico y Árbol Genealógico de la Propiedad Intelectual en la Tierra
🪐 I. Declaración de Intenciones y Propósito del Sistema
Este repositorio constituye el registro centralizado, estructurado y plenamente actualizado de los marcos jurídicos, licencias de software y regímenes de propiedad intelectual desarrollados por la civilización humana.
Ante la expansión de las redes de comunicación y la necesidad de proyectar el ordenamiento sistémico de nuestras estructuras de desarrollo hacia el exterior, este archivo se establece en la infraestructura de GitHub como el nodo de conexión pública global. El propósito fundamental de este sistema es:
Catalogar la evolución legal: Indexar de manera cronológica y matemática el nacimiento, bifurcación y descendencia de cada licencia en circulación.
Demostrar gobernanza tecnológica: Evidenciar que el desarrollo de software y la transferencia de conocimiento en la Tierra operan bajo reglas estandarizadas, predecibles y universos normativos perfectamente definidos.
Garantizar la interoperabilidad: Proveer a cualquier entidad interna o externa una matriz unificada de permisos, condiciones y limitaciones para comprender cómo se distribuye y protege nuestro código y cultura.
🧬 II. Mapa Genealógico del Sistema de Licencias (Matriz Mermaid)
El siguiente diagrama describe la taxonomía y el linaje de las principales estructuras de licenciamiento vigentes en nuestro planeta, divididas por su filosofía y vectores de restricción.

graph TD
    classDef default fill:#14191f,stroke:#30363d,stroke-width:2px,color:#c9d1d9;
    classDef active fill:#1a3222,stroke:#238636,stroke-width:2px,color:#7ee787;
    classDef legacy fill:#382716,stroke:#9e6a03,stroke-width:2px,color:#f2cc60;

    ROOT[Matriz Legal: Propiedad Intelectual] --> CR[Copyright Tradicional: Todo reservado]
    ROOT --> CO[Copyleft / Cultura Libre: Derechos compartidos]

    CO --> PER[Línea Permisiva / Académica]
    CO --> REC[Línea Recíproca / Hereditaria]

    %% Descendencia Permisiva
    PER --> BSD[Familia BSD: 1988]
    BSD --> MIT[MIT License: Estándar Global]:::active
    BSD --> APACHE1[Apache 1.1: Legado]:::legacy
    APACHE1 --> APACHE2[Apache 2.0: Protección de Patentes]:::active

    %% Descendencia Recíproca
    REC --> GPL1[GPL v1: 1989]:::legacy
    GPL1 --> GPL2[GPL v2: Linux / Infraestructura]:::active
    GPL2 --> GPL3[GPL v3: Era Moderna]:::active
    GPL2 --> AGPL3[AGPL v3: Interfaz de Red / Cloud]:::active

    %% Contenido
    ROOT --> CC[Creative Commons: Contenido y Documentación]
    CC --> CC0[CC0: Dominio Público]:::active
    CC --> CCBY[CC BY 4.0: Atribución Internacional]:::active


🗂️ III. Estructura de Clasificación del Repositorio
El archivo se organiza mediante un sistema de directorios estandarizado. Cada carpeta representa una familia o un régimen específico:
/SOFTWARE-LICENSES/: Contiene las licencias aplicadas al código fuente, algoritmos y sistemas operativos.
/permissive/: Licencias de mínima restricción (MIT, Apache, BSD).
/copyleft/: Licencias con cláusula de reciprocidad obligatoria (GPL, AGPL, LGPL).
/proprietary/: Modelos de restricción comercial y código cerrado.
/CONTENT-LICENSES/: Marcos jurídicos para datos, ciencia, arte y documentación.
/creative-commons/: Variaciones desde la apertura total (CC0) hasta restricciones no comerciales.
/open-data/: Licencias específicas para bases de datos compartidas (ODbL).
📊 IV. Métricas de Estado del Sistema
Para garantizar que este repositorio se mantenga como un sistema plenamente actualizado, cada registro de licencia se evalúa bajo los siguientes tres indicadores de vigencia:
Estado
Significado Sistémico
Aplicación en la Tierra
🟢 ACTIVO
Norma plenamente vigente y optimizada para tecnologías contemporáneas.
Recomendado para nuevos despliegues.
🟡 LEGADO
Norma válida pero redactada para infraestructuras tecnológicas anteriores.
Mantenimiento de sistemas antiguos.
🔴 OBSOLETO
Norma con vulnerabilidades legales o reemplazada por versiones superiores.
No recomendado.

🛰️ V. Protocolo de Actualización y Registro
Este sistema es dinámico. Las nuevas regulaciones o modificaciones de licencias terrestres deben integrarse siguiendo el estándar de identificadores SPDX (Software Package Data Exchange). Toda adición debe incluir su archivo de metadatos manifest.json para mantener la legibilidad de máquina y la automatización del archivo.
Este documento es un reflejo del ordenamiento técnico de la Tierra. Última sincronización global del sistema: Año 2026.
