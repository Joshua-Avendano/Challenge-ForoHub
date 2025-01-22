# Challenge-ForoHub

ForoHub es una aplicación desarrollada en Java con el entorno IntelliJ para el desafío del curso &quot;Practicando Spring Framework: Challenge Foro Hub&quot; de ONE + Alura Latam.  Este challenge se basa en una API REST para poder hacer consutlas CRUD a los tópicos en la base de datos.

## Características ⚙️

1. **Registro de tópicos:** Permite registrar topicos con su título, mensaje, fecha de creación, status, autor y curso.
2. **Listar tópicos:** Listado de todos los topicos registrados en la base de datos.
3. **Búsqueda de un tópico en específico:** Permite buscar un tópico en específico por medio del ID.
4. **Actualización de tópicos:** Permite actualizar un tópico ya previamente creado.
5. **Elimación de tópicos:** Permite eliminar el tópico deseado por medio del ID.
6. **Login con spring security y JWT para autenticación y autorización:** Permite generar un JWT para autenticar a un usuario por medio de un inicio de sesión.
7. **Persistencia de datos:** Toda la información se guarda en una base de datos MySQL.


## Instalación ⚙️

Simplemente se requiere clonar este proyecto en el repositorio local, y luego ejecutarlo con un IDE acorde (como IntelliJ, Eclipse, etc) desde el método <code>main</code> de la clase <code>ForoHubApplication</code>.

Dado que la aplicación trabaja con una base de datos, se requiere un servidor MySQL 8.0.40 o superior previamente instalado. (Se proveen scripts SQL para pruebas).

Importante: No olvidar declarar las variables de entorno que se utilizan en <code>application.properties</code>.


## Tecnologías Utilizadas 🛠️

- Java 21
- Insomina para simulación del cliente
- Swagger para documentación automática
- Spring Boot
- Flyway para la gestión de migraciones de base de datos.
- MySQL
- Maven

## Requisitos 🔧

- Java 17 o 21
- MySQL
- Insonmia o Postman para simular el cliente
- IDE como IntelliJ IDEA o Eclipse (opcional, para editar el código).
