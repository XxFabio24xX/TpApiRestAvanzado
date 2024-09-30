# TP API REST AVANZADO

Este proyecto es una API REST avanzada construida con Spring Boot, que abarca diversos conceptos y funcionalidades avanzadas como la creación del modelo de datos usando JPA/Hibernate, reutilización de código, queries personalizadas, paginación y la integración de OpenAPI (Swagger) para probar la API.

## Tecnologías Utilizadas

- **Java**: Lenguaje de programación.
- **JPA (Java Persistence API)**: Para la persistencia de datos.
- **Hibernate Envers**: Para la auditoría de cambios en las entidades.
- **H2 Database**: Base de datos en memoria para pruebas.
- **OpenAPI/Swagger** (Para documentación y pruebas de la API)
- **Gradle**: Lenguaje de construcción de proyectos.


## Configuración del Proyecto

### Requisitos

- JDK 17 o superior
- Gradle
- IDE (IntelliJ IDEA)
- H2 Database
- Envers
- JPA
- Hibernate
- Java Persistence API
- OpenAPI/Swagger


## Estructura del Proyecto
- **audit**: Contiene la clase Revision.
- **config**: Contiene la clase CustomRevisionListener para la auditoría.
- **controllers**: Contiene el controlador de Persona, Autor y Localidad.
- **entities**: Contiene las entidades Autor, Base, Domicilio, Libro, Localidad, Persona.
- **repositories**: Contiene el repositorio de Persona, Autor y Localidad.
- **services**: Contiene la interfaz AutorService, PersonaService y LocalidadService, con sus Implementaciones.

## Ejecutar el Proyecto
### Paso 1
Descargar el repositorio de GitHub.

```bash
git clone https://github.com/XxFabio24xX/TPApiRestAvanzado
```
### Paso 2
Abrir el proyecto en IntelliJ IDEA.
### Paso 3
Ejecutar el archivo 'Inicial1Application.java' dentro del proyecto.

### Paso 4
- En el navegador: 
  - Abrir la consola de H2: ("localhost:8080/h2-console")\
  [H2 Console](http://localhost:8080/h2-console)
  - Abrir la consola de OPEN API: ("localhost:8080/swagger-ui/index.html")\
  [OPEN API](http://localhost:8080/swagger-ui/index.html)

## Autor

- **Nombre**: Fabio Escudero
- **Comisión**: 3K10
- **Materia**: Desarrollo de Software
- Universidad Técnologica Nacional, Mendoza