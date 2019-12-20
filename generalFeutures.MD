# Aspects to consider

- A software (independent of type) is built relatively like any other product, following a series of stages or faces that involve the production process, quality models among other aspects in general.

- A software (independent of type) is built relatively like any other product, following a series of stages or faces that involve the production process, quality models among other aspects in general

## Software life cycle

1. Problem Statement
2. Analysis
3. Design
4. Implementation
5. Tests
6. Delivery and output 

## Metodologías de desarrollo

* Una metodología es una colección de prodedimientos, técnicas, herramientas y dcumentos auxiliares que ayudan a los desarrolladores de software en sus esfuerzos por implementar nuevos sistemas de información.

* Una metodología esta formada por fases, cada una de las cuales se pueden dividir en sub-fases, que guiarán a los desarolladores de sistemas a elegir las técnicas mas apropiadas en cada momento del proyecto y tambien a la planificación, gestionarlo, controlarlo y evaluarlo(Avison y Fitzgeral, 2006).

#### Metodologías Tradicionales.

Estructura:
![alt text][logo]

[logo]: https://github.com/ITDevSolution/StrooperTest/blob/master/src/common/images/metodologias.png "Estructura de Metodologías Tradicionales"

RUP : Rational unifined process, el RUP  es una metología muy grande enfocada a proyectos muy grandes y muy robustos donde se ataca el ciclo de vida del software, de ahi se puede derivar otras metodologías como ICONIX que trata de obtener elementos importantes del RUP para poder atacar proyectos. Bien esto nos brinda una serie de documentos o artefactos que nosotros lo podemos utilizar para nuestro proyecto de software.

#### Metodologías Agiles

*Metodología agil*
![alt text][logo1]

[logo1]: https://github.com/ITDevSolution/StrooperTest/blob/master/src/common/images/metodologíasAgiles.png "SCRUM"

SCRUM es una metodoogía agil que define documentos o artefactos que se utilizan en el backlog para convertir en sprint según el equipo de trabajo que conforman el proyecto.

#### DESARROLLO DE UNA APP MOVIL.
una App también es un software por ende cuenta con estas mismas etapas,sin embargo en el contexto móvil pueden ser agrupados en:

*Etapas de trabajo simultaneo entre el diseñador y desarrollador*
![alt text][logo2]
[logo2]: https://github.com/ITDevSolution/StrooperTest/blob/master/src/common/images/ciclo_life_app.png "Etapas de un trabajo simultaneo"

1. Conceptualización.
2. Definición.
3. Diseño.
4. Desarrollo.
5. Publicación.

##### CONCEPTUALIZACIÓN
* El resutado de esta etapa es una idea de aplicacion, que tiene en cuenta las necesidades y problemas de los usuarios. La idea responde a una investigación preliminar y a la posterior comprobación de la viabilidad del concepto.

- Ideación
- Investigación
- Formalización de la idea.

**PARA QUE?**
Debemos definir cual es el propósito general de la Aplicación, a que categoría corresponde...

- Entretenimiento.
- Sociales.
- Productividad.
- Educativas e informativas.
- Creacionales.
- Otras...

**ASPECTOS A TENER EN CUENTA**
Quienes van hacer:

- Clientes y usuarios.

- Competencia. (buscar aplicaciones referentes a nuestro proyecto, si existen o no hacer una comparativa y buscar error para mejorarlos en nuestra aplicacion)

- Nicho de mercado: A quien va enfocada la aplicaciom, hasta donde queremos llegar o cuales son los usuarios a los que queremos llegar.
Debemos tener en cuenta aspectos demograficos, de dnde son? que edades? que perfil? etc.

- Herramientas y recursos.

- Plataforma.

- Dispositivos y aspectos técnicos.

- Alcance: Caracteristicas que va a tener la aplicacion..

- Requisitos Funcionales: Depende de los requerimientos del clientes. Como ejemplo podría ser el registro de usuarios, y mediante que sera construido(sqLITE, usar preferents o usar una base de datos remota).

- Requisitos No funcionales: Atributos de calidad, aspectos de respuesta, usabilidad, rendimiento etc.

#### DEFINICION

* En este caso el proceso se describe con detalle a los usuarios para quienes se diseñerá la aplicacipon, usando metodologías como las historia de usuario.

* Tambien aquí se sientan las bases de la funcionalidad, lo cual determinará el alcance real del proyecto, la complejidad de diseño y programacion de la App.

- Definición de usuarios.
- Definición funcional: esta parte estará determinado el alcance real del proyecto, la complejidad que se requiere al momento de desarrollar la aplicación.

**HISTORIAS DE USUARIO.**

*"Las historias de usuario corresponden a descripciones cortas y simples de una funcionalidad escrita desde la perspectiva de la persona que necesite una nueva capacidad de un sistema, por lo general el usuario, área de negocio o cliente."

* Una de las ventajas de las historias de usuario es que puedan escribirse en un lenguaje natural fácil de interpretar así como el nivel de detalle que puede contemplarse.

Ejemplo de estructura de usuario: 

* Cuando escribimos historias de usuario debemos tener en cuenta el rol(quien cuenta la historia), la funcionalidad y el resultado al que queremos llegar.

TITULO |
--- |
Como [ROL], quiero hacer
[FUNCIONALIDAD] con el
objetivo de [BENEFICIO]

ejemplo:

*Yo como usuario quiero hacer el registro jugadores dentro de la aplicacion
con el objetivo de tener usuarios con quien competir.*

Ejemplo en documento:
![alt text][historia_usuario]
[historia_usuario]: https://github.com/ITDevSolution/StrooperTest/blob/master/src/common/images/historia_usuario.png "Historia de usuario en documento"

La historia de usuario tambien debe contener los criterios de aceptación de la funcionalidad el cual incluye el contexto, evento y resultado.