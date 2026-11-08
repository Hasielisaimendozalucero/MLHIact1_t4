# Actividad 1: Introducción a Spring Boot - Configuración y Primeros Controladores

Este proyecto consiste en una aplicación web desarrollada con **Spring Boot**, **Java 17** y **Maven**, desplegada en un entorno de producción basado en contenedores Docker mediante **Render**.

---

## 📌 Datos de la Entregable

* **Estudiante:** Hasiel Isaí Mendoza Lucero
* **Asignatura:** Programación Web
* **Puerto asignado:** `8081`
* **Entorno de producción (VPS/PaaS):** Render.com

---

## 🚀 Endpoints Disponibles

La aplicación cuenta con 2 controladores que atienden peticiones HTTP GET:

### 1. Endpoint: Identificador del Estudiante
* **Ruta:** `/mi-nombre`
* **Método:** `GET`
* **Respuesta:** Texto con el nombre del proyecto y desarrollador.
* **URL de prueba:** `https://mlhiact1-t4.onrender.com/mi-nombre`

### 2. Endpoint: Listado de Materias
* **Ruta:** `/materias`
* **Método:** `GET`
* **Respuesta:** Lista simulada de materias en formato JSON.
* **URL de prueba:** `https://mlhiact1-t4.onrender.com/materias`

### 3. Endpoint: Estado del Servidor
* **Ruta:** `/estado`
* **Método:** `GET`
* **Respuesta:** Mensaje simple de confirmación del estado del servicio.
* **URL de prueba:** `https://mlhiact1-t4.onrender.com/estado`

---

## 🛠️ Tecnologías Utilizadas

* **Java:** 17
* **Framework:** Spring Boot 3.x / Web
* **Gestor de dependencias:** Maven
* **Contenedor:** Docker (`eclipse-temurin:17-jdk-alpine`)
* **Control de versiones:** Git & GitHub

---

## 💻 Ejecución Local

Para compilar y ejecutar el proyecto localmente en tu máquina:

1. Compilar el archivo ejecutable `.jar`:
   ```bash
   ./mvnw clean package -DskipTests
