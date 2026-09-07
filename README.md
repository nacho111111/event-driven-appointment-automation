# Sistema de Automatización de Reservas y Mensajería

## Descripción General

Sistema de automatización orientado a la gestión de citas y comunicación con clientes mediante integración de servicios externos.

El flujo está orquestado con Make y conecta:

- 📩 WhatsApp Cloud API  
- 📆 Cal.com  
- 📊 Google Sheets  

El sistema permite responder mensajes, registrar reservas y enviar recordatorios sin intervención manual.

---

## Problema

La gestión manual de citas implicaba:

- Envío manual de confirmaciones
- Registro manual de reservas
- Riesgo de errores administrativos
- Pérdida de tiempo en tareas repetitivas

---

## Solución Implementada

Se diseñaron flujos automatizados basados en eventos que permiten:

- ✔ Responder automáticamente mensajes entrantes
- ✔ Enviar recordatorios programados
- ✔ Registrar reservas en una base estructurada
- ✔ Sincronizar eventos entre plataformas

El sistema funciona bajo una arquitectura orientada a eventos, donde cada servicio genera acciones que activan flujos automáticos.

---


