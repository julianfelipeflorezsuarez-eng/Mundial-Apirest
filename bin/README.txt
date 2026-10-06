CRUD-MUNDIAL-FELIPE-APIREST

1. Importar como proyecto Maven en Spring Tools Suite / Eclipse.
2. Java 17.
3. Configurar MongoDB en src/main/resources/application.properties.
   - Local: dejar la URI por defecto.
   - Atlas: reemplazar la propiedad por tu URI de Atlas o usar la variable de entorno MONGODB_URI.
4. Ejecutar como Spring Boot App.
5. Abrir http://localhost:8093/

La interfaz consume la API REST real mediante fetch.
La API mantiene GET, POST, PUT y DELETE y las validaciones/restricciones del proyecto.
