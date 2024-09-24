# Trabajo Final de Máster en Ciberseguridad

Este repositorio contiene una aplicación web vulnerable diseñada para el Trabajo Final de Máster (TFM) en Ciberseguridad, enfocada en la **identificación y mitigación de vulnerabilidades en arquitecturas de microservicios**. A través de este proyecto, se aplican metodologías estándar de ciberseguridad para el análisis de un sistema basado en microservicios, detallando las fases de reconocimiento, escaneo, explotación y mitigación de vulnerabilidades.

## Descripción del proyecto

El propósito principal de este proyecto es analizar una arquitectura de microservicios en un entorno práctico, identificando vulnerabilidades críticas que podrían comprometer la seguridad del sistema y proponiendo soluciones efectivas para mitigarlas. Este enfoque ayuda a comprender mejor los desafíos de seguridad inherentes a los microservicios y proporciona recomendaciones para mejorar la protección de la información y los datos.

### Funcionalidades clave de la aplicación:

- **Gestión de reservas de hoteles y vuelos:** La aplicación permite a los usuarios gestionar sus reservas de manera intuitiva.
- **Interacción con microservicios:** La aplicación utiliza una arquitectura de microservicios para manejar diferentes partes del sistema, como la gestión de usuarios, las reservas y la disponibilidad de servicios.
- **Base de datos MySQL:** La información se almacena de manera centralizada en una base de datos relacional, permitiendo la persistencia de datos relevantes del sistema.

## Estructura de la aplicación

### 1. Frontend de la aplicación

El frontend de la aplicación está desarrollado utilizando las siguientes tecnologías:

- **HTML:** Para la estructura de las páginas web, creando una interfaz de usuario intuitiva.
- **CSS:** Para diseñar y estilizar la apariencia, asegurando una experiencia de usuario coherente.
- **JavaScript:** Para agregar interactividad a la aplicación, permitiendo la manipulación dinámica de contenido.

### 2. Backend de la aplicación

El backend de la aplicación está desarrollado utilizando **Spring Boot**, un marco de trabajo en Java que facilita la creación de aplicaciones robustas y escalables. El backend se conecta a una base de datos **MySQL**, donde se almacena toda la información relevante de usuarios, reservas y disponibilidad.

### 3. Arquitectura de microservicios

La aplicación sigue una arquitectura de microservicios, donde:

- Cada microservicio tiene una función específica, lo que permite modularidad y escalabilidad.
- Los microservicios están conectados a la base de datos MySQL que almacena toda la información del sistema.

## Ejecución y más información

Para más detalles sobre el análisis de vulnerabilidades y los pasos para ejecutar el proyecto, consulta el archivo PDF del trabajo completo que se encuentra en este repositorio: **[TFM_Ciberseguridad.pdf]**.

---

**Autor:** Andrew Steeve Ramirez Guzman (Ar4mir3z)
**Repositorio creado para:** Trabajo Final de Máster en Ciberseguridad
