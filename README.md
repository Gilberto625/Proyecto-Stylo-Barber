# 💈 Stylo Barber Connect

**Sistema Integral de Gestión para Barbería**

Stylo Barber Connect es una plataforma web y móvil diseñada para optimizar las operaciones de una barbería moderna, permitiendo la gestión completa de citas, productos, ventas, inventario, notificaciones, entregas, reportes, empleados y más. Este proyecto busca digitalizar los procesos tradicionales y mejorar la eficiencia, experiencia del cliente y rentabilidad del negocio.

---

## 📌 Contenido

* [Descripción General](#-descripción-general)
* [Objetivo del Proyecto](#-objetivo-del-proyecto)
* [Alcance](#-alcance)
* [Tipos de Usuario](#-tipos-de-usuario)
* [Módulos del Sistema](#-módulos-del-sistema)
* [Requerimientos Funcionales](#-requerimientos-funcionales)
* [Requerimientos No Funcionales](#-requerimientos-no-funcionales)
* [Requerimientos Técnicos](#-requerimientos-técnicos)
* [Cronograma General](#-cronograma-general)

---

## 🧾 Descripción General

Stylo Barber Connect es un sistema multiplataforma (web + móvil) que permite gestionar:

* Citas y agenda inteligente
* Catálogo de servicios
* Catálogo e inventario de productos
* Procesamiento de ventas y pagos
* Apartados
* Envíos y entregas
* Notificaciones automáticas
* Gestión de empleados y roles
* Métricas y reportes avanzados
* Políticas de negocio
* Soporte y ayuda

Su diseño permite optimizar la operación diaria, reducir errores humanos, mejorar el flujo de trabajo y aumentar la satisfacción del cliente mediante recordatorios, anticipos y disponibilidad en tiempo real.

---

## 🎯 Objetivo del Proyecto

* Crear un sistema integral para digitalizar la operación completa de una barbería.
* Permitir que clientes agenden citas en línea con disponibilidad inteligente.
* Controlar ventas y productos tanto en línea como presencial.
* Automatizar notificaciones, recordatorios y procesos de pago.
* Proveer reportes estratégicos para la toma de decisiones.
* Garantizar seguridad, rapidez y facilidad de uso.

---

## 📌 Alcance

Esta solución está diseñada para funcionar en:

* Navegadores web modernos
* Aplicación móvil Android/iOS
* Equipos de escritorio (admin/secretaria)

Incluye backend, frontend web, aplicaciones móviles y base de datos centralizada.

---

## 👥 Tipos de Usuario

### **1. Administrador**

Control total del sistema: empleados, reportes, inventario, políticas, servicios y productos.

### **2. Secretaria**

Gestión diaria de citas, agenda, inventario, ventas presenciales, pagos y validaciones.

### **3. Barbero / Colaborador**

Actualiza tiempos de servicio, visualiza su agenda, recibe notificaciones de citas.

### **4. Cliente**

Agendar citas, comprar productos, recibir notificaciones, ver historial, apartados y pagos.

---

## 🧩 Módulos del Sistema

### 🔐 Autenticación

* Registro
* Inicio de sesión
* Login con Google y Facebook
* Recuperación de contraseña
* 2FA
* Bloqueo por intentos fallidos

### 👤 Perfiles

* Actualización de datos
* Foto de perfil
* Preferencias
* Eliminación de cuenta

### 📅 Gestión de Citas

* Agendar con disponibilidad inteligente
* Reprogramación
* Cancelación
* Check-in
* Agenda diaria/semana/mes

### 💇 Servicios

* Creación / edición / eliminación
* Catálogo visible para clientes
* Duración configurable

### 🛒 Productos e Inventario

* Catálogo
* Stock
* Entradas/salidas
* Alertas
* Apartados con anticipo

### 💳 Pagos y Ventas

* Venta en línea
* Venta presencial
* Anticipos
* Integración con Mercado Pago
* Transferencias con validación

### 🚚 Envíos y Entregas

* Recoger en local
* Moto mandado
* Envíos nacionales (futuro)

### 📢 Notificaciones

* Email
* SMS / WhatsApp
* Push
* Recordatorios automáticos

### 🧑‍🏫 Empleados y Roles

* Registro
* Especialidades
* Permisos
* Horarios de trabajo

### 📊 Reportes y Métricas

* Ventas
* Servicios más solicitados
* Productos más vendidos
* Días de alta demanda

### ⚙️ Configuración y Políticas

* Horarios
* Festivos
* Anticipos
* Cancelaciones
* Promociones

### 🆘 Soporte

* FAQ
* Tickets
* Chat de soporte

---

## ✅ Requerimientos Funcionales (resumen)

El sistema cuenta con **170 procedimientos**, organizados en:

* Autenticación (12)
* Perfiles (10)
* Citas (20)
* Servicios (12)
* Productos e inventario (15)
* Ventas y pagos (15)
* Envíos (10)
* Notificaciones (14)
* Empleados (12)
* Reportes (19)
* Configuración (12)
* Soporte (9)

Cada uno especifica entradas, procesos, reglas y salidas.

---

## ⚡ Requerimientos No Funcionales

* Sistema rápido (<2 segundos por operación crítica)
* Seguridad de contraseñas con bcrypt
* Tokens JWT
* Expiración y validación de enlaces
* Auditoría completa
* Escalabilidad y concurrencia
* API segura con HTTPS
* Validaciones en tiempo real

---

## 🛠️ Requerimientos Técnicos

### Software

* Backend: Node.js / Express
* Base de datos: MongoDB Atlas
* Frontend web: React
* Aplicación móvil: React Native (Expo)
* Integraciones:

  * Mercado Pago
  * Servicios de correo
  * Notificaciones push

### Hardware (mínimo en barbería)

* PC o laptop
* Smartphone Android/iOS
* Conexión a internet estable

---

## 📅 Cronograma General

(El cronograma detallado se genera por semanas desde septiembre 2025.)

Incluye etapas de análisis, diseño, desarrollo, pruebas, integración, documentación y entrega.

---

## 🧑‍💻 Autores

* **Hernández Hernández Gilberto**
* **Cayetano García Jorge Miguel**

Docente: **MTRO. José de Jesús González Torres**
Huejutla de Reyes, Hidalgo — Octubre 2025
