# diagrama

# 🧩 Proyecto: Arquitectura TechStore

## 📌 Descripción

Este proyecto corresponde a la actividad formativa de la semana 7, donde se analiza la arquitectura de base de datos de una tienda online llamada **TechStore**.

El objetivo es representar de manera visual cómo funciona el sistema, considerando la base de datos, la seguridad en las transacciones y las instrucciones necesarias para su funcionamiento.

---

## 🎯 Objetivo

Diseñar un diagrama de arquitectura que muestre:

* Tipo de base de datos (SQL)
* Gestión de usuarios, productos y transacciones
* Medidas de seguridad
* Tipos de instrucciones (DDL, DML, DCL)
* Flujo de datos entre los componentes del sistema

---

## 🗄️ Base de Datos

Se utilizó una base de datos **SQL** debido a:

* Manejo de datos estructurados
* Relaciones entre entidades (usuarios, productos, compras)
* Integridad de datos (propiedades ACID)
* Seguridad en transacciones

---

## 🔐 Seguridad

Se consideraron los siguientes mecanismos:

* Consultas parametrizadas (prevención de SQL Injection)
* Validación de datos en el backend
* Uso de HTTPS
* Autenticación de usuarios
* Control de acceso según roles

---

## ⚙️ Instrucciones de Base de Datos

### DDL (Data Definition Language)

* CREATE
* ALTER

### DML (Data Manipulation Language)

* INSERT
* UPDATE
* DELETE

### DCL (Data Control Language)

* GRANT
* REVOKE

---

## 🖥️ Arquitectura del Sistema

El sistema está compuesto por:

* **Frontend:** interfaz de usuario (web/app)
* **Backend:** servidor que procesa la lógica y valida datos
* **Base de Datos:** almacenamiento de usuarios, productos y transacciones

El flujo de datos se realiza desde el usuario hacia el backend y luego hacia la base de datos, aplicando medidas de seguridad en cada etapa.

---

## 📄 Archivos del proyecto

* `TechStore_Arquitectura.pdf` → Diagrama de arquitectura
* `README.md` → Descripción del proyecto

---

## 🚀 Cómo visualizar

1. Descargar el archivo PDF
2. Abrirlo con cualquier visor de PDF

---

## 👨‍💻 Autor

Trabajo desarrollado como actividad académica.
