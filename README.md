Repositorio del grupo de investigación TecnoLeTTra (Tecnologías del Lenguaje, la Terminología y la Traducción) de la Universitat Jaume I para el desarrollo y mantenimiento de recursos ontológicos y lingüísticos relacionados con el modelo Ontodic.
## Objetivo
La organización del repositorio busca facilitar:
- la reutilización de recursos,
- la reproducibilidad del trabajo,
- la trazabilidad terminológica,
- y la separación clara entre modelo, dominios, diccionarios, recursos y corpus.
## Estructura del repositorio
El repositorio se organiza en cinco carpetas principales:
### `Ontodic/`
Esta carpeta reúne los principales componentes del modelo Ontodic. Incluye recursos como OntodicCore.owl o Relations.owl, además de recursos específicos por idioma como MorphUnits.owl.
Cada componente podría documentarse con mayor detalle:
- OntodicCore.owl: 
- Relations.owl:
- MorphUnits:
- Idiomas soportados y en desarrollo[ARD1]
### `Domain/`
Esta carpeta está destinada a almacenar los dominios temáticos sobre los que se vaya trabajando.
Actualmente incluye:
- Movilidad autónoma y sostenible (DomainMobility.owl)
Se está(n) desarrollando el/los siguiente(s) dominio(s):[ARD2]
- ¿Aceite de oliva?
### `Dictionaries/`
Contiene ontologías completas y enriquecidas que integran todos los imports necesarios.
Actualmente se cuenta con:
- Ecodrive.owl (diccionario sobre movilidad autónoma y sostenible)
Se está(n) desarrollando el/los siguiente(s) diccionario(s):[ARD3]
- 
### `Corpus/`
Contiene los corpus y materiales empleados durante el proceso de construcción de los diccionarios, validación y revisión terminológica y conceptual. 
### `Resources/`
Contiene los recursos léxicos y terminológicos utilizados en el desarrollo de las ontologías. El objetivo de esta carpeta es facilitar la trazabilidad de los términos empleados y reutilizar los recursos lingüísticos generados durante los proyectos. 

---
## Recursos y documentación relacionada (artículo que explique Ontodic con algo más de detalle)[ARD4]
2025 Alcina, A. “ONTODIC: a model of linguistic knowledge representation based on description logic”, en Terminology, 31:2 (2025), pp. 208–237.  [Fecha aceptación: 23-07-2024]. https://doi.org/10.1075/term.23030.alc
---
## Autores[ARD5]
Amparo Alcina (Universitat Jaume I)
## Contribuidores

## Instituciones participantes

---
## Licencia
Es recomendable incluir un fichero LICENSE con la información relativa a los permisos de uso, reutilización y distribución de las ontologías y recursos contenidos en el repositorio.
Como referencia pueden consultarse:
- https://github.com/edmcouncil/auto/blob/master/LICENSE (la de la ontología de automóviles que me pasaste)
- https://github.com/city-knowledge-graphs/kg-course-valgrai/blob/main/LICENSE.md (del curso de Ernesto)

[ARD1]Esto habría que completarlo sí se considera necesario añadir una pequeña explicación sobre cada componente de Ontodic
[ARD2]Habría que completarlo/editarlo cuando se empiece a trabajar en otros proyectos o dominios
[ARD3]Igual que en Domain. Habría que completarlo/editarlo cuando se empiece a trabajar en otros proyectos o dominios
[ARD4]Esto es opcional pero puede estar bien tenerlo. De momento el artículo más reciente sobre Ontodic que encontré en la página web es este. Si se considera necesario se puede poner y si hay alguna otra publicación posterior que complete la explicación se puede sustituir esta referencia y poner la nueva o añadirla simplemente
[ARD5]Los tres siguentes puntos también son opcionales, pero al ser un proyecto académico creo que puede estar bien mencionarlo
