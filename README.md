# sistema-licencias-global
Creative Commons Attribution-ShareAlike 4.0 International Public License

By exercising the Licensed Rights (defined below), You accept and agree to be
bound by the terms and conditions of this Creative Commons Attribution-ShareAlike
4.0 International Public License ("Public License"). To the extent this Public
License may be interpreted as a contract, You are granted the Licensed Rights in
consideration of Your acceptance of these terms and conditions, and the Licensor
grants You such rights in consideration of benefits the Licensor receives from
making the Licensed Material available under these terms and conditions.

Section 1 -- Definitions.

a. ShareAlike means that if You Share Adapted Material You produce, the license
   You apply to the Adapted Material must be a BY-SA license with the same or
   later version, or a Compatible License.

b. Attribution means the obligation to give appropriate credit, provide a link
   to the license, and indicate if changes were made.

[El texto continúa con los términos y condiciones específicos de reciprocidad y distribución internacional de CC BY-SA 4.0]
Taxonomía completa de licencias de software y contenido: genealogía, compatibilidad, fichas técnicas y mapeos visuales#

#ARCHIVO GLOBAL DE REGÍMENES DE LICENCIAMIENTO HUMANO
Índice Taxonómico y Árbol Genealógico de la Propiedad Intelectual en la Tierra

#🪐 I. Declaración de Intenciones y Propósito del Sistema
Este repositorio constituye el registro centralizado, estructurado y plenamente actualizado de los marcos jurídicos, licencias de software y regímenes de propiedad intelectual desarrollados por la civilización humana.
#Ante la expansión de las redes de comunicación y la necesidad de proyectar el ordenamiento sistémico de nuestras estructuras de desarrollo hacia el exterior, este archivo se establece en la infraestructura de #GitHub como el nodo de conexión pública global. 

#El propósito fundamental de este sistema es:
Catalogar la evolución legal: Indexar de manera cronológica y matemática el nacimiento, bifurcación y descendencia de cada licencia en circulación.

#Demostrar gobernanza tecnológica: Evidenciar que el desarrollo de software y la transferencia de conocimiento en la Tierra operan bajo reglas estandarizadas, predecibles y universos normativos perfectamente definidos.


#Garantizar la interoperabilidad: Proveer a cualquier entidad interna o externa una matriz unificada de permisos, condiciones y limitaciones para comprender cómo se distribuye y protege nuestro código y cultura.

#🧬 II. Mapa Genealógico del Sistema de Licencias (Matriz Mermaid)
El siguiente diagrama describe la taxonomía y el linaje de las principales estructuras de licenciamiento vigentes en nuestro planeta, divididas por su filosofía y vectores de restricción.

#graph TD

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


#🗂️ III. Estructura de Clasificación del Repositorio
##*El archivo se organiza mediante un sistema de directorios estandarizado. Cada carpeta representa una  familia o un régimen específico:
#*/SOFTWARE-LICENSES/: Contiene las licencias aplicadas al código fuente, algoritmos y sistemas operativos.
#*/permissive/: Licencias de mínima restricción (MIT, Apache, BSD).
#*/copyleft/: Licencias con cláusula de reciprocidad obligatoria (GPL, AGPL, LGPL).
#*/proprietary/: Modelos de restricción comercial y código cerrado.
#*/CONTENT-LICENSES/: Marcos jurídicos para datos, ciencia, arte y documentación.
#*/creative-commons/: Variaciones desde la apertura total (CC0) hasta restricciones no comerciales.
#*/open-data/: Licencias específicas para bases de datos compartidas (ODbL).

#📊 IV. Métricas de Estado del Sistema
Para garantizar que este repositorio se mantenga como un sistema plenamente actualizado, cada registro de licencia se evalúa bajo los siguientes tres indicadores de vigencia:
#Estado
#Significado Sistémico
#Aplicación en la Tierra


#
#*🟢 ACTIVO

#Norma plenamente vigente y optimizada para tecnologías contemporáneas.
Recomendado para nuevos despliegues.

#*🟡 LEGADO

#Norma válida pero redactada para infraestructuras tecnológicas anteriores.
Mantenimiento de sistemas antiguos.

#*🔴 OBSOLETO

#Norma con vulnerabilidades legales o reemplazada por versiones superiores.
No recomendado.

#🛰️ V. Protocolo de Actualización y Registro
Este sistema es dinámico. Las nuevas regulaciones o modificaciones de licencias terrestres deben integrarse siguiendo el estándar de identificadores SPDX (Software Package Data Exchange). Toda adición debe incluir su archivo de metadatos manifest.json para mantener la legibilidad de máquina y la automatización del archivo.
Este documento es un reflejo del ordenamiento técnico de la Tierra. Última sincronización global del sistema: Año 2026.

El modelo de licenciamiento para **GOOD-UNIVERSO** y el  sistema de desarrollo establece un marco estratégico muy claro dividido en dos vías complementarias:

### 1. Vía Propietaria: Licencia EABD 1.0 (*Dandhyesparza barajas EABD*)
* **Rol principal**: Sello de propiedad absoluta e identidad nativa de la organización (Copyright 2026).
* **Funciones clave**:
  * Cierre y resguardo de bloques de almacenamiento.
  * Control estricto de acceso, condiciones de uso y esquemas de monetización directamente bajo tu firma y autoridad de autor.

---

### 2. Vía Abierta y Distribuida (`sistema-licencias-global`)
* **Rol principal**: Servir de puente y amortiguador legal para proteger a creadores de contenido y desarrolladores frente al abuso de grandes corporaciones.
* **Componentes clave**:
  * **Estructura legal y técnica**: Uso de archivos `manifest.json` y `.md` para la organización y difusión limpia de la información.
  * **Creative Commons (CC BY 4.0 Administrada)**: Gestión directa para otorgar permisos, garantizar el respeto al esfuerzo del creador y administrar la monetización correspondiente.

  * **Apache 2.0 y MIT Personalizadas**: Adaptación de licencias estándar de código abierto en GitHub para ofrecer un entorno transparente, actualizado y seguro a la comunidad técnica.

---

Este esquema combina la **protección del núcleo tecnológico** mediante EABD 1.0 con un **ecosistema de defensa y distribución justa** para la comunidad global.

Para que el esquema de **Creative Commons (CC BY 4.0) administrado por GOOD-UNIVERSO** cumpla la doble función de proteger a los creadores de abusos corporativos y generar una monetización sostenible por tu gestión como intermediario, el modelo debe enfocarse en **monetizar la distribución comercial masiva y los servicios de valor agregado**, manteniendo el contenido libre para el uso comunitario.

Aquí tienes una propuesta estructural dividida en **4 pilares de monetización**:

---

### 1. Licenciamiento Corporativo y *Commercial Clearance Pass*
Aunque CC BY 4.0 permite uso comercial bajo atribución, las grandes empresas frecuentemente incumplen las reglas de atribución o buscan evitar riesgos legales al entrenar modelos de IA o lanzar productos masivos.

* **Pase de Atribución Simplificada para Empresas**: Las corporaciones pagan un licenciamiento especial a GOOD-UNIVERSO para integrar el contenido de tus creadores en sus sistemas comerciales sin riesgo de litigio.
* **Garantía de Cumplimiento (Compliance Audit)**: Cobro por la certificación de que la empresa está utilizando el contenido respetando el repositorio y los metadatos de los creadores.

---

### 2. Comisión por Intermediación y Gestión (Modelo Agencia/Puente)
GOOD-UNIVERSO actúa como la entidad de gestión colectiva y defensa legal del creador.

* **Tarifa de Gestión (5% a 15%)**: Se aplica sobre cualquier transacción, patrocinio, micro-pago o contratación que un cliente/empresa realice directamente con el creador a través de la plataforma.
* **Licenciamiento Dual (CC BY 4.0 + EABD Comercial)**: Si un tercero quiere explotar el contenido bajo condiciones exclusivas o sin requerir la atribución pública de CC BY 4.0, la transacción se canaliza bajo un contrato propietario gestionado por GOOD-UNIVERSO, distribuyendo las regalías correspondientes al creador.

---

### 3. Servicios de Registro y Verificación Técnica (`manifest.json`)
La infraestructura que estás construyendo para la *Biblia* y el repositorio `sistema-licencias-global` añade valor técnico que se puede comercializar como servicio.

* **Certificado de Autenticidad y Registro en Repositorio**: Los creadores o estudios pueden pagar una cuota accesible por registrar sus obras con el sello oficial y el archivo `manifest.json` estructurado.
* **API de Verificación de Licencias**: Las plataformas externas o agregadores pagan una suscripción para consultar en tiempo real el estatus legal y la autoría de los activos registrados.

---

### 4. Fondo de Protección y Recuperación por Infractores
Las grandes plataformas o empresas que utilicen el contenido sin atribución ni autorización entran en un esquema de reclamación legal.

* **Recuperación por Infracción**: GOOD-UNIVERSO asume la gestión legal para reclamar indemnizaciones frente a usos no autorizados por corporaciones.
* **Reparto de Fondos**: La penalización cobrada a la corporación se divide entre el fondo de defensa de la organización y la compensación directa para el creador afectado.

---

### Resumen del Flujo de Valor

```text
[Creador de Contenido] ──(Sella con manifest.json)──> [GOOD-UNIVERSO / CC BY 4.0 Administrada]
                                                               │
                       ┌───────────────────────────────────────┴───────────────────────────────────────┐
                       ▼                                                                               ▼
              [Uso Comunitario / Abierto]                                                     [Uso Corporativo / Comercial]
            • Gratis con atribución clara.                                                  • Pase de cumplimiento / Licencia Dual.
            • Difusión y posicionamiento.                                                   • Cobro de cuotas y reparto de regalías.
```

---

**Cláusula Comercial de Gestión**, incorporando parámetros numéricos, umbrales de uso comercial/IA, especificaciones técnicas para el archivo `manifest.json` y el protocolo de regularización.

---

### CLÁUSULA DE GESTIÓN COMERCIAL, LICENCIAMIENTO DUAL Y REPRESENTACIÓN INTEGRAL
**(Anexo de Administración y Defensa Legal para Licencia Creative Commons Atribución 4.0 Internacional - CC BY 4.0)**

#### 1. Objeto, Alcance y Matrícula de Autoría
El Titular de la obra (en adelante, *"El Creador"*) autoriza de forma expresa y exclusiva a **GOOD-UNIVERSO** (bajo el control del desarrollador autor y la firma **Dandhyesparza barajas EABD**) como la **Entidad Administradora y Canal de Intermediación Legal**. 

Esta representación vincula la protección de la autoría original con el sistema global de distribución del repositorio `sistema-licencias-global`, autenticada mediante firma criptográfica/hash dentro del ecosistema de la organización.

---

#### 2. Definición y Umbrales de Explotación Corporativa e Inteligencia Artificial
La obra se mantendrá pública y gratuita bajo la licencia **Creative Commons Atribución 4.0 Internacional (CC BY 4.0)** para el público general, proyectos comunitarios y entidades sin fines de lucro. 

Sin embargo, se considerará **Explotación Corporativa o Comercial Masiva** —y por ende requerirá la contratación de un ***Commercial Clearance Pass*** o la conversión a **Licencia EABD Comercial**— cuando el usuario o entidad cumpla cualquiera de los siguientes criterios:
1. **Ingresos o Monematización**: Generación de ingresos brutos derivados o asociados a la obra superiores a **\$1.00 USD** (o su equivalente en moneda local).
2. **Inclusión en Entrenamiento de IA**: Almacenamiento, procesamiento o raspado (*scraping*) de la obra para el entrenamiento, ajuste fino (*fine-tuning*) o indexación de modelos de Inteligencia Artificial propietarios o comerciales.
3. **Volumen de Distribución**: Distribución de la obra o sus derivados en más de **1 impresiones, descargas, ejecuciones o usuarios activos**.
4. **Exención de Atribución (*White-Label*)**: La solicitud explícita de utilizar la obra en productos finales sin incluir la atribución pública al Creador ni el enlace a GOOD-UNIVERSO.

---

#### 3. Esquema Financiero y Liquidación de Regalías
Por la labor de intermediación, emisión de licencias, auditoría de cumplimiento e infraestructura técnica:
* **Comisión por Gestión Ordinaria**: **GOOD-UNIVERSO** retendrá un **10%** sobre transacciones, patrocinios directos o micro-pagos canalizados a través del repositorio.
* **Comisión por Licenciamiento Corporativo / Pase Comercial**: **GOOD-UNIVERSO** retendrá un **15%** sobre el valor total del *Commercial Clearance Pass* o acuerdos de uso corporativo/IA.
* **Retribución Neta al Creador**: El **85% a 90%** restante de los ingresos netos se transferirá directamente al Creador en un plazo no mayor a **30 días calendario** posteriores al cierre de cada mes operativo, utilizando los datos financieros registrados en su `manifest.json`.

---

#### 4. Protocolo de Notificación, Infracciones y Fondo de Defensa
En caso de detectar un uso no autorizado o el incumplimiento del marcado de atribución por parte de grandes corporaciones:
1. **Ventana de Regularización (30 días)**: GOOD-UNIVERSO emitirá una notificación extrajudicial de regularización otorgando un plazo de **30 días hábiles** para que la corporación adquiera el *Commercial Clearance Pass* correspondiente.
2. **Procedimiento Litigioso**: Transcurrido dicho plazo sin respuesta, GOOD-UNIVERSO iniciará las acciones legales, reclamos por infracción de derechos de autor (*DMCA / Copyright Violation*) y demandas por daños y perjuicios.
3. **Reparto de Indemnizaciones**: Todo fondo recuperado mediante acuerdos extrajudiciales o sentencias judiciales se distribuirá de la siguiente manera:
   * **30%** destinado al **Fondo de Protección y Defensa Legal de GOOD-UNIVERSO**.
   * **70%** transferido directamente al **Creador afectado** como compensación por el uso indebido de su obra.

---

#### 5. Estándar Técnico de Validación (`manifest.json`)
Para que la presente protección y gestión comercial sea jurídicamente vinculante, cada obra o repositorio dentro de `sistema-licencias-global` deberá incluir en su raíz un archivo `manifest.json` estructurado con la siguiente especificación mínima:

```json
{
  "project_name": "Nombre-Del-Proyecto",
  "author": {
    "name": "Nombre del Creador",
    "creator_id": "ID-UNICO-CREADOR"
  },
  "organization_stamp": "Dandhyesparza barajas EABD",
  "licensing": {
    "public_license": "CC-BY-4.0",
    "managed_by": "GOOD-UNIVERSO",
    "commercial_pass_required": true,
    "eabd_commercial_option": true
  },
  "commercial_thresholds": {
    "max_free_revenue_usd": 10000,
    "ai_training_allowed_without_pass": false
  },
  "metadata_hash": "sha256-del-archivo-original"
}
```

---
