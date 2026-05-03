# 🛒 Sistema de Ventas en Java

![Java](https://img.shields.io/badge/Java-17-orange)
![Status](https://img.shields.io/badge/status-active-success)
![License](https://img.shields.io/badge/license-MIT-blue)

Sistema de ventas desarrollado en **Java**, diseñado para gestionar productos, clientes y ventas de manera eficiente. Ideal para pequeños y medianos negocios.

---

## 📌 Descripción

Este sistema permite administrar todo el flujo de ventas desde un solo lugar, incluyendo:

- Gestión de productos
- Control de inventario
- Registro de clientes
- Procesamiento de ventas
- Generación de reportes

El objetivo es ofrecer una solución sencilla, rápida y funcional para el control comercial.

---

## ⚙️ Características

- 📦 CRUD de productos (crear, leer, actualizar, eliminar)
- 👤 Gestión de clientes
- 💰 Registro de ventas
- 📊 Reportes básicos de ventas
- 🔐 Sistema de autenticación de usuarios
- 📉 Control de stock en tiempo real
- 🧾 Generación de tickets

---

## 🏗️ Tecnologías Utilizadas

- Java (JDK 11 o superior)
- Swing / JavaFX (interfaz gráfica)
- JDBC (conexión a base de datos)
- MySQL o SQLite

---

## 📂 Estructura del Proyecto

```bash
src/
├── main/
│   ├── java/
│   │   ├── model/        # Clases de datos (Producto, Cliente, Venta)
│   │   ├── dao/          # Acceso a datos (JDBC)
│   │   ├── service/      # Lógica de negocio
│   │   ├── view/         # Interfaces gráficas
│   │   └── controller/   # Controladores
│   └── resources/        # Configuraciones
