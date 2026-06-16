# Sistema de Reservas
---
Este proyecto es una aplicación de Backend desarrollada en Java orientada a la gestión y control de reservas. El sistema está estructurado utilizando el patrón de diseño de Capas, separando la lógica de negocio mediante Entidades (Entities) y Objetos de Acceso a Datos (DAOs).

## 🛠️ Tecnologías y Librerías utilizadas
- Java (Lógica principal del backend)

- Lombok (Para la generación automática de código como @Data, constructores y encapsulamiento)

- Swagger / OpenAPI v3 (Para la documentación y exposición de los endpoints de la API)

- Patrón DAO (Data Access Object) (Para la abstracción y persistencia de datos)

- Entities (Modelado del negocio en clases Java)

## ⚙️ Estructura de la Entidad Principal
El núcleo del sistema maneja la entidad Reserva, la cual procesa los siguientes datos reales:

- ID de la Reserva: Identificador único del registro.

- ID del Usuario: Asociación con el cliente que realiza la solicitud.

- Cantidad de Personas: Control del aforo o espacio requerido para la reserva.

- Fecha y Hora: Manejo de la temporalidad exacta usando la API nativa LocalDateTime.

## 🚀 Cómo ejecutar el proyecto localmente
Clona este repositorio:

```
git clone https://github.com/Enmanuel-Miranda/TU_REPOSITORIO_AQUI.git
```
Abre el proyecto en tu IDE preferido (como IntelliJ IDEA o NetBeans).

Asegúrate de tener habilitado el plugin de Lombok en tu IDE para que reconozca las anotaciones de datos.

Ejecuta la clase principal del proyecto.

✒️ Creado por Enmanuel **Miranda**
