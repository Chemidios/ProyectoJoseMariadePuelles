# ProyectoJoseMariadePuelles
# RA2: Planificación general del proyecto

## a) Recopilación de información

Para el desarrollo del proyecto se ha llevado a cabo una fase inicial de recopilación de información con el objetivo de definir correctamente los requisitos y las tecnologías a emplear.

Se han analizado plataformas existentes de gestión de torneos de videojuegos como **Battlefy**, **Challonge** o **Toornament**, observando sus funcionalidades principales, diseño y experiencia de usuario.

Asimismo, se ha investigado sobre las tecnologías vistas durante el ciclo formativo, como:

* Desarrollo de aplicaciones Android mediante **Kotlin y Jetpack Compose**.
* Desarrollo de aplicaciones híbridas con **Ionic y Angular**.
* Creación de servicios backend con **APIs REST** y bases de datos remotas en **Render** y **Firebase**.

Esta información ha permitido definir un proyecto realista, acorde al nivel del curso y alineado con los contenidos del módulo.

## b) Estudio de viabilidad técnica

El proyecto es técnicamente viable, ya que se apoya en herramientas y lenguajes trabajados durante el ciclo formativo.

* El **backend** se implementará mediante una **API REST** que gestionará usuarios, torneos e inscripciones, conectada a una base de datos remota alojada en **Render**.
* El **frontend** se dividirá en dos partes:

  * Aplicación móvil Android desarrollada con **Kotlin y Jetpack Compose**.
  * Aplicación web híbrida desarrollada con **Ionic**.

Todas las herramientas necesarias (**Android Studio, IntelliJ, Visual Studio Code, Render, Firebase**) están disponibles de forma gratuita o ya han sido utilizadas previamente en el curso, lo que garantiza la viabilidad técnica del proyecto sin necesidad de formación adicional.

## c) Identificación de fases del proyecto

El proyecto se divide en varias fases claramente diferenciadas:

1. **Análisis y diseño**: definición de requisitos, diseño de la arquitectura del sistema, diseño de la base de datos y bocetos de las pantallas.
2. **Desarrollo del backend**: implementación de la API REST, autenticación de usuarios, gestión de torneos e integración con la base de datos.
3. **Desarrollo de la aplicación móvil**: creación de la interfaz con Jetpack Compose e integración con el backend.
4. **Desarrollo de la aplicación híbrida**: creación de la web con Ionic e integración con la misma API.
5. **Pruebas y validación**: comprobación del correcto funcionamiento de todas las funcionalidades.
6. **Documentación y entrega**: elaboración de la memoria del proyecto y preparación de la entrega final.

Cada fase tiene una duración estimada y se ejecuta de forma secuencial para asegurar una correcta implementación.

## d) Objetivos y alcance del proyecto

### Objetivo principal

Desarrollar una **plataforma multiplataforma** que permita la gestión de torneos de videojuegos de forma sencilla e intuitiva.

### Objetivos específicos

* Permitir el registro e inicio de sesión de usuarios.
* Mostrar un listado de torneos disponibles.
* Permitir la inscripción de usuarios en torneos.
* Mostrar al usuario los torneos en los que participa.
* Desarrollar una aplicación móvil y una web híbrida conectadas al mismo backend.

### Alcance

El alcance del proyecto se limita a la **gestión básica de torneos y usuarios**, sin incluir funcionalidades avanzadas como pagos online o retransmisiones en directo.

## e) Actividades necesarias

Para el desarrollo del proyecto será necesario realizar las siguientes actividades:

* Análisis de requisitos y definición de funcionalidades.
* Diseño de la base de datos y la arquitectura del sistema.
* Programación del backend y creación de la API REST.
* Desarrollo de la aplicación móvil Android.
* Desarrollo de la aplicación web híbrida.
* Pruebas de integración entre frontend y backend.
* Corrección de errores y mejoras.
* Documentación técnica y memoria del proyecto.

## f) Necesidades de financiación

El proyecto no requiere una inversión económica significativa.

Se utilizarán planes gratuitos de **Render** y herramientas de desarrollo gratuitas. En caso de necesitar mejoras de rendimiento o disponibilidad, se contempla un coste máximo aproximado de **5–10 € mensuales**, aunque no es imprescindible para la puesta en marcha del proyecto.

---

# RA3: Planificación según fases y funciones

## a) Secuenciación de las tareas en función de las necesidades de implementación

Las tareas del proyecto se han secuenciado teniendo en cuenta las dependencias técnicas entre los distintos módulos del sistema.

1. **Análisis y diseño**: definición de la arquitectura general, la base de datos y las funcionalidades.
2. **Desarrollo del backend**: núcleo del sistema del que dependen los frontends.
3. **Desarrollo de los frontends**: aplicación móvil y web híbrida, que pueden realizarse de forma paralela.
4. **Pruebas y documentación final**.

## b) Determinación de los recursos y la logística necesaria para cada tarea

* **Análisis y diseño**: ordenador, conexión a internet, herramientas de documentación y diseño.
* **Desarrollo backend**: entorno de desarrollo, servidor Render, base de datos remota y herramientas de prueba de APIs.
* **Desarrollo app móvil**: Android Studio, emuladores o dispositivo físico.
* **Desarrollo app web híbrida**: Visual Studio Code, Ionic CLI y navegador web.
* **Pruebas**: emuladores, navegadores y herramientas de depuración.
* **Documentación**: procesador de textos y herramientas de exportación a PDF.

La logística del proyecto se centraliza en un único puesto de trabajo.

## c) Identificación de las necesidades de permisos y autorizaciones

Para la ejecución del proyecto no son necesarios permisos administrativos ni autorizaciones externas.

Únicamente se requiere:

* Disponer de cuentas en plataformas de despliegue como **Render**.
* Acceso a un repositorio de control de versiones (**GitHub**).
* Permisos de acceso a la base de datos remota configurada para el proyecto.

No se manejan datos personales reales ni información sensible, por lo que no se requieren autorizaciones legales adicionales.

## d) Planificación temporal de las tareas (cronograma)

| Fase              | Tareas principales           | Duración  |
| ----------------- | ---------------------------- | --------- |
| Análisis y diseño | Requisitos, arquitectura, BD | 1 semana  |
| Backend           | API, autenticación, BD       | 2 semanas |
| App móvil         | Pantallas, lógica, API       | 2 semanas |
| App web           | Páginas, lógica, API         | 2 semanas |
| Pruebas           | Integración y correcciones   | 1 semana  |
| Documentación     | Memoria y entrega            | 1 semana  |

## e) Identificación y planificación de las actividades necesarias para cada fase

* **Análisis y diseño**: definición de requisitos funcionales, diseño de la arquitectura del sistema, diseño de la base de datos y bocetos de interfaces.
* **Backend**: creación de modelos, desarrollo de la API REST, implementación de la autenticación, conexión con la base de datos y pruebas de endpoints.
* **App móvil**: creación de pantallas con Jetpack Compose, gestión de estados, integración con la API y pruebas en emulador.
* **App web**: desarrollo de páginas con Ionic, consumo de la API REST y pruebas en navegador.
* **Pruebas**: pruebas funcionales, detección y corrección de errores, validación de la integración completa.
* **Documentación**: redacción de la memoria del proyecto y preparación de la entrega final.

Esta identificación permite controlar el progreso del proyecto y asegurar que no se omiten tareas importantes.

## f) Valoración económica del proyecto

La valoración económica del proyecto es mínima, ya que se utilizan herramientas gratuitas y recursos propios.

* Software de desarrollo: **0 €**.
* Hosting backend y base de datos (Render): **0 €**.
* Hosting web: **0 €**.

**Coste total estimado del proyecto: 0 €.**

En caso de ampliación futura, el coste podría incrementarse hasta aproximadamente **10 € mensuales** sin comprometer la viabilidad del proyecto.
