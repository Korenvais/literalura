# LiterAlura 📚

**LiterAlura** es una aplicación desarrollada en **Java** con **Spring Boot**, diseñada para gestionar y consultar un catálogo literario de libros y autores. Aprovecha la integración con la API de **Gutendex** para acceder a datos de libros de dominio público y ofrece una experiencia interactiva en la administración y exploración de contenido literario.

## Características principales 🚀
- **Búsquedas avanzadas**: Encuentra libros y sus autores tan solo con ingresar el titulo.
- **Gestión de catálogo**: Registra nuevos libros y establece relaciones entre autores y sus obras.
- **Persistencia de datos**: Usa una base de datos relacional **PostgreSQL** para almacenar y consultar información de manera eficiente.
- **Integración con Gutendex**: Obtén datos actualizados en formato JSON directamente desde la API.
- **Generación de estadísticas**: Analiza la información del catálogo para obtener datos relevantes.

## Tecnologías utilizadas 🛠️
- **Java** y **Spring Boot**: Base del desarrollo backend.
- **PostgreSQL**: Almacenamiento y gestión de datos relacionales.
- **Gutendex API**: Fuente de datos literarios de dominio público.
- **JSON**: Manejo de datos estructurados para comunicación entre API y la aplicación.

## Cómo empezar 🚀
1. Clona este repositorio:
   ```bash
   git clone https://github.com/tu-usuario/literalura.git
   ```
2. Configura la base de datos PostgreSQL y actualiza el archivo `application.properties` con tus credenciales.
3. Ejecuta la aplicación con:
   ```bash
   ./mvnw spring-boot:run
   ```
4. Explora el catálogo y disfruta gestionando contenido literario.

## Próximos pasos 📈
- Implementación de una interfaz gráfica para mejorar la experiencia del usuario.
- Mejora de los algoritmos de búsqueda y recomendación.
- Soporte para múltiples idiomas y configuraciones personalizadas.

## Contribuciones 💡
¡Las contribuciones son bienvenidas! Si deseas colaborar, abre un issue o envía un pull request.

## Contacto

Para más información, puedes contactarme en [LinkedIn](https://www.linkedin.com/in/arykorenvais/).

---

**LiterAlura**: Descubre y gestiona la magia de los libros, una obra a la vez. 🌟
