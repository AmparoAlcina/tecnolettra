# ONTODIC Resources

Repositorio del grupo de investigación TecnoLeTTRA (Tecnologías del Lenguaje, la Terminología y la Traducción) de la Universitat Jaume I para el desarrollo, mantenimiento y publicación de recursos basados en el modelo ONTODIC.

El repositorio reúne módulos ontológicos de referencia, bases de conocimiento terminológicas y recursos lingüísticos vinculados a proyectos de investigación sobre terminología, representación del conocimiento, tecnologías lingüísticas y espacios de datos.

## Objetivo del repositorio

El objetivo principal de este repositorio es facilitar la organización, consulta, reutilización y mantenimiento de recursos terminológicos y ontológicos desarrollados a partir del modelo ONTODIC.

En particular, el repositorio busca favorecer:

* la reutilización de recursos terminológicos y lingüísticos;
* la trazabilidad entre términos, conceptos, dominios y fuentes documentales;
* la separación clara entre modelo, dominios temáticos y bases de conocimiento terminológicas;
* la interoperabilidad de los recursos OWL;
* la documentación y preservación de los recursos generados en proyectos de investigación;
* la preparación de los recursos para su explotación en tecnologías lingüísticas, inteligencia artificial y espacios de datos.

## Modelo ONTODIC

ONTODIC es un modelo de representación del conocimiento lingüístico y terminológico basado en lógica descriptiva. El modelo permite representar de forma diferenciada la dimensión conceptual y la dimensión lingüística de la terminología.

En ONTODIC, los conceptos se representan como clases, mientras que los términos y variantes denominativas se representan como individuos vinculados a dichas clases conceptuales. Esta estructura permite integrar en un mismo recurso información conceptual, terminológica y lingüística, como términos, variantes, contextos de uso, lengua, categoría gramatical, tipo morfológico, género, número y metadatos descriptivos.

Referencia principal:

Alcina, A. (2025). “ONTODIC: a model of linguistic knowledge representation based on description logic”. *Terminology. International Journal of Theoretical and Applied Issues in Specialized Communication*, 31(2), 208–237. https://doi.org/10.1075/term.23030.alc

## Estructura actual del repositorio

En la versión actual del repositorio, los principales recursos OWL generados en el marco del proyecto EcoDrive TermSpace se encuentran disponibles en el directorio raíz. Esta organización se mantiene para facilitar la trazabilidad con la documentación técnica y los anexos de justificación del proyecto, en los que se describe la disponibilidad de los ficheros OWL en el repositorio GitHub.

Entre los recursos OWL actualmente disponibles se incluyen:

* `OntodicCore.owl`: módulo central del modelo ONTODIC, que contiene las clases y propiedades necesarias para organizar la información lingüística, terminológica y conceptual.
* `DomainMobility.owl`: módulo de dominio correspondiente a la movilidad autónoma y sostenible, basado en el árbol de campo desarrollado en el proyecto.
* `mediosTransporte.owl`: base de conocimiento terminológica de la rama Medios de transporte.
* `InfraestructurasFisicas.owl`: base de conocimiento terminológica de la rama Infraestructuras físicas.
* `ActoresDeLaMovilidad.owl`: base de conocimiento terminológica de la rama Actores de la movilidad.
* `AccionesYProcesos.owl`: base de conocimiento terminológica de la rama Acciones y procesos.
* `ModalidadesMovilidad.owl`: base de conocimiento terminológica de la rama Modalidades de movilidad.
* `GestionMovilidad.owl`: base de conocimiento terminológica de la rama Gestión de la movilidad.
* `TecnologiasMovilidad.owl`: base de conocimiento terminológica de la rama Tecnologías de la movilidad sostenible y autónoma.
* `GestionDeLaSostenibilidad.owl`: base de conocimiento terminológica de la rama Gestión de la sostenibilidad.
* `Ecodrive.owl`: base de conocimiento integrada que agrupa la información procedente de las bases de conocimiento terminológicas de rama.

La carpeta `Diccionarios/` se reserva para una posible organización futura de bases de conocimiento terminológicas integradas o diccionarios ontoterminológicos desarrollados a partir del modelo ONTODIC. En la versión actual, los ficheros OWL principales se mantienen en el directorio raíz para preservar la correspondencia con la documentación de entrega del proyecto.

## Recursos desarrollados en EcoDrive TermSpace

El proyecto EcoDrive TermSpace se centra en la creación de recursos terminológicos multilingües para el ámbito de la movilidad autónoma y sostenible.

En el marco de este proyecto se han generado:

* un módulo de dominio de movilidad: `DomainMobility.owl`;
* ocho bases de conocimiento terminológicas correspondientes a las ramas principales del árbol de campo;
* una base de conocimiento integrada: `Ecodrive.owl`;
* recursos terminológicos y lingüísticos asociados;
* documentación metodológica sobre creación, revisión, interoperabilidad y publicación de los recursos OWL.

Las ocho ramas principales del dominio son:

1. Medios de transporte.
2. Infraestructuras físicas.
3. Actores de la movilidad.
4. Acciones y procesos.
5. Modalidades de movilidad.
6. Gestión de la movilidad.
7. Tecnologías de la movilidad sostenible y autónoma.
8. Gestión de la sostenibilidad.

## Financiación

Los recursos sobre movilidad autónoma y sostenible incluidos en este repositorio se han desarrollado en el marco del proyecto **EcoDrive TermSpace. Terminología multilingüe para la movilidad autónoma sostenible**.

| Dato                            | Información                                                                      |
| ------------------------------- | -------------------------------------------------------------------------------- |
| Título                          | Terminología multilingüe para la movilidad autónoma sostenible                   |
| Acrónimo                        | EcoDrive TermSpace                                                               |
| Nº de expediente                | INREED/2024/2                                                                    |
| Entidad financiadora            | Generalitat Valenciana. Conselleria de Innovación, Industria, Comercio y Turismo |
| Duración                        | Enero 2025 – Mayo 2026                                                           |
| Entidad coordinadora            | Pangeanic                                                                        |
| Entidades participantes         | Pangeanic; Universitat Jaume I; ValgrAI, como entidad subcontratada              |
| Presupuesto general             | 575.374,02 €                                                                     |
| Presupuesto Universitat Jaume I | 225.150,73 €                                                                     |

## Descripción de los recursos OWL

### `OntodicCore.owl`

`OntodicCore.owl` contiene el núcleo del modelo ONTODIC. Este módulo proporciona las clases, propiedades y estructuras necesarias para representar información terminológica y lingüística.

Permite organizar, entre otros aspectos:

* términos como individuos;
* conceptos como clases;
* información lingüística asociada a los términos;
* contextos de uso;
* lengua;
* categoría gramatical;
* tipo morfológico;
* género y número;
* anotaciones y metadatos descriptivos.

### `DomainMobility.owl`

`DomainMobility.owl` contiene la estructura conceptual del dominio de la movilidad autónoma y sostenible. Este módulo se basa en el árbol de campo desarrollado durante el proyecto EcoDrive TermSpace y organiza el dominio en ocho ramas principales y sus correspondientes subramas.

Este recurso sirve como módulo de dominio para clasificar conceptos y términos relacionados con movilidad, transporte, infraestructuras, actores, procesos, modalidades de movilidad, gestión, tecnologías y sostenibilidad.

### Bases de conocimiento terminológicas de rama

Las bases de conocimiento terminológicas de rama contienen los términos, conceptos e información lingüística correspondientes a cada una de las ocho ramas principales del dominio.

Cada una de estas bases de conocimiento se implementa como fichero OWL editable en Protégé y permite trabajar de forma modular sobre una parte específica del dominio.

Los ficheros de rama son:

* `mediosTransporte.owl`
* `InfraestructurasFisicas.owl`
* `ActoresDeLaMovilidad.owl`
* `AccionesYProcesos.owl`
* `ModalidadesMovilidad.owl`
* `GestionMovilidad.owl`
* `TecnologiasMovilidad.owl`
* `GestionDeLaSostenibilidad.owl`

### `Ecodrive.owl`

`Ecodrive.owl` es la base de conocimiento integrada del proyecto EcoDrive TermSpace. Agrupa la información procedente de las bases de conocimiento terminológicas de rama y permite consultar de forma conjunta los conceptos, términos, variantes denominativas, contextos de uso e información lingüística del dominio de la movilidad autónoma y sostenible.

## Acceso y reutilización

Los recursos OWL pueden consultarse, descargarse y abrirse con herramientas de edición ontológica como Protégé.

Algunos recursos importan módulos de referencia del propio repositorio. Por ello, se recomienda mantener la estructura actual de los ficheros o utilizar las rutas publicadas en el repositorio para asegurar que los imports se resuelvan correctamente.

Cuando los recursos se abran desde URL, se recomienda comprobar que las rutas de importación apuntan a las versiones publicadas correspondientes.

## Cita recomendada

Para citar el modelo ONTODIC:

Alcina, A. (2025). “ONTODIC: a model of linguistic knowledge representation based on description logic”. *Terminology. International Journal of Theoretical and Applied Issues in Specialized Communication*, 31(2), 208–237. https://doi.org/10.1075/term.23030.alc

Para citar los recursos desarrollados en el marco del proyecto EcoDrive TermSpace, se recomienda hacer referencia al proyecto y al repositorio:

TecnoLeTTRA/UJI. *EcoDrive TermSpace: terminología multilingüe para la movilidad autónoma sostenible*. Recursos ONTODIC y bases de conocimiento terminológicas sobre movilidad autónoma y sostenible. Universitat Jaume I.

## Autoría y contribución

Estos recursos han sido desarrollados por el grupo de investigación TecnoLeTTRA de la Universitat Jaume I, en el marco de proyectos de investigación sobre terminología, tecnologías lingüísticas, representación del conocimiento y espacios de datos.

Investigadora principal y responsable del modelo ONTODIC:

* M. Amparo Alcina Caudet, Universitat Jaume I.

En el proyecto EcoDrive TermSpace han participado Pangeanic, como entidad coordinadora, y la Universitat Jaume I, a través del grupo TecnoLeTTRA. ValgrAI ha intervenido como entidad subcontratada para tareas de apoyo técnico, formación, asesoramiento y difusión. El proyecto ha contado asimismo con asesoramiento experto del Instituto Universitario de Investigación en Tráfico y Seguridad Vial (INTRAS) de la Universitat de València.

## Licencia

Los recursos de este repositorio se publican con fines de investigación, documentación, reutilización académica y desarrollo tecnológico.

Se recomienda consultar el fichero `LICENSE` del repositorio para conocer las condiciones específicas de uso, reutilización, modificación y distribución de los recursos.

## Contacto

Grupo de investigación TecnoLeTTRA
Universitat Jaume I
https://tecnolettra.uji.es/
