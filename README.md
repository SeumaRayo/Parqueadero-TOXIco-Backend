# 🅿️ Parqueadero TOXI-co

**Parqueadero TOXI-co** es un sistema de gestión de parqueaderos diseñado para ofrecer una solución integral y escalable tanto para usuarios ocasionales como para vehículos con membresía. Este software está pensado para facilitar el control de entradas, salidas, facturación, tarifas y administración de espacios en diferentes ubicaciones.

---

## 🚀 Funcionalidades principales

- **Registro de vehículos con o sin membresía**.
- **Administración de membresías por vehículo** (similar a SmartFit).
- **Gestión de empleados y turnos de trabajo**.
- **Control de acceso y registro de ingresos**.
- **Facturación automática para usuarios casuales**.
- **Tarifas configurables por ciudad o país**.
- **API RESTful construida con Spring Boot**.

---

## 🧱 Estructura del proyecto

El proyecto está organizado por módulos, cada uno encargado de una funcionalidad específica del sistema:

- **auth/**: autenticación y validación de usuarios.
- **usuario/**: administración de usuarios y roles.
- **tipo-vehiculo/**: configuración de tipos de vehículos y tarifas.
- **config/**: configuración general del servidor y la base de datos.

---

## 🛠️ Tecnologías usadas

- **Backend**: Spring Boot
- **Base de datos**: PostgreSQL
- **Framework**: Spring Web, Spring Security, Spring Data JPA
- **Control de versiones**: Git + Git Flow

---

## 🔧 Instalación

1. Clona el repositorio:

   ```bash
   git clone https://github.com/SeumaRayo/Parqueadero-TOXIco-Backend
   cd Parqueadero-TOXIco-Backend
   
2. Configura tu archivo application.properties para la base de datos y otras configuraciones:

  ```bash
  spring.datasource.url=jdbc:postgresql://localhost:5432/tu_base_de_datos
  spring.datasource.username=usuario
  spring.datasource.password=contraseña
  spring.jpa.hibernate.ddl-auto=update
  spring.jpa.properties.hibernate.format_sql=true
  ```
3. Compila y ejecuta el proyecto con Maven o Gradle:

  Si usas Maven:
      ```bash
      ./mvnw spring-boot:run
    ```

  Si usas Gradle:
      ```bash
      ./gradlew bootRun
      ```
