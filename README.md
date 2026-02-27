<p align="center">
  <img src="https://img.shields.io/badge/status-active-success" />
  <img src="https://img.shields.io/badge/backend-django-green" />
  <img src="https://img.shields.io/badge/database-mysql-blue" />
</p>

<p align="center">
  <img src="./docs/banner.png" alt="Hotel Lillo PMS banner" />
</p>

<h1 align="center">Hotel Lillo PMS</h1>

<p align="center">
Sistema de gestión hotelera diseñado específicamente para un hotel familiar de 32 habitaciones.
</p>

---

## Descripción general

**Hotel Lillo PMS** es un sistema de gestión hotelera desarrollado para centralizar y optimizar
las operaciones diarias del Hotel Lillo.  
El sistema elimina procesos manuales propensos a errores y proporciona información en tiempo
real sobre el estado operativo del hotel.

La solución está enfocada en **eficiencia operativa**, **reducción de tiempos administrativos**
y **mejora de la experiencia del huésped**, manteniendo una interfaz simple e intuitiva para el personal.

---

## Características principales

- Sistema de reservas con verificación instantánea de disponibilidad
- Módulo de check-in y check-out con facturación automática
- Gestión centralizada de 32 habitaciones:
  - Suites
  - Matrimoniales
  - Twin
  - Familiares
- Control de tarifas por temporada:
  - Alta
  - Media
  - Baja
- Registro histórico de huéspedes y preferencias
- Gestión de servicios adicionales:
  - Llamadas
  - Minibar
- Reportes automáticos de:
  - Ocupación
  - Ingresos
- Sistema de roles:
  - Administrador
  - Recepcionista
- Interfaz optimizada para reducir tiempos de operación

---

## Objetivos del sistema

- Eliminar dobles reservas y errores de cálculo manual
- Reducir el tiempo promedio de check-out de **20 a 5 minutos**
- Optimizar entre **3 y 4 horas diarias** de gestión telefónica
- Mejorar la satisfacción del cliente en al menos un **40%**
- Proporcionar información en tiempo real del estado del hotel

---

## Arquitectura y metodología

El sistema está desarrollado bajo la metodología **Scrum**, permitiendo iteraciones rápidas
y adaptación a las necesidades reales del hotel.

La arquitectura sigue un enfoque monolítico basado en Django, con separación clara entre:
- Lógica de negocio
- Vistas
- Templates
- Persistencia de datos

---

## Tecnologías utilizadas

- Python 3
- Django 4.2
- MySQL
- HTML5
- CSS
- JavaScript (validaciones del lado del cliente)

---

## Requisitos previos

Antes de ejecutar el proyecto, asegúrese de tener instalado:

- Python 3.10 o superior
- MySQL Server
- MySQL Client
- pip

Dependencia principal:
```bash
pip install "django==4.2.*"
