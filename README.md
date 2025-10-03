# ⚙️ Backend - CartApp (Spring Boot)

Este es el **backend** del proyecto **CartApp**, una aplicación para gestionar un carrito de compras, desarrollada con **Spring Boot**.
Expone una **API REST** que es consumida por el frontend hecho en **React + Vite + TypeScript**.

## 🚀 Tecnologías utilizadas

* ☕ Java 17
* 🍃 Spring Boot 3
* 📦 Maven
* 🗄️ JPA
* 🐘 Base de datos relacional (MySQL)
* 🛠️ Controladores 

## 📂 Estructura del proyecto

* `controllers/` → Endpoints REST
* `models/` → Entidades de base de datos
* `repositories/` → Repositorios con JPA
* `services/` → Lógica de negocio
* `resources/application.properties` → Configuración de la aplicación
* `resources/import.sql` → Datos iniciales de la BD

## ⚙️ Configuración

En el archivo `application.properties`, configurar la conexión a la base de datos:

```properties
spring.datasource.url=
spring.datasource.username=
spring.datasource.password=
spring.datasource.driver-class-name=
spring.jpa.database-platform=
spring.jpa.show-sql=
spring.jpa.hibernate.ddl-auto=
logging.level.org.hibernate.SQL=
```

## ▶️ Ejecución

1. Clonar el repositorio
2. Configurar la base de datos en `application.properties`
3. Ejecutar API
4. La API estará disponible en:

   ```
   http://localhost:8080
   ```

## 🔗 Repositorios relacionados

- [Frontend - React + TS](https://github.com/crisomarjs/frontend-cartapp)
- [Backend - Spring Boot](https://github.com/crisomarjs/backend-cartapp-springboot)
