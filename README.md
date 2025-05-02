# Sección: Testimonios de Usuarios

Esta sección forma parte del proyecto **Adopta un Sabio**, una plataforma diseñada para conectar la sabiduría de los adultos mayores con las inquietudes de las nuevas generaciones.

## 🎯 Objetivo

Permitir que los usuarios que han interactuado con los sabios compartan un testimonio breve, significativo y auténtico sobre su experiencia.

## ✅ Características

- **Carrusel automático e interactivo** para mostrar testimonios.
- **Formulario validado** con:
  - Nombre
  - Testimonio (máximo 92 caracteres)
  - Fecha (ingresada por el usuario)
- **Captcha tipo suma (1-9)** con verificación visual (check verde).
- **Contador de caracteres** en tiempo real.
- **Botón dinámico** que cambia entre “Deja aquí tu testimonio” y “Cerrar formulario”.
- **Conexión en tiempo real** con Google Sheets vía Google Apps Script.
- **Datos almacenados** en la hoja `TESTIMONIOS` del archivo `CONSULTAS`.

## 🔗 Enlace al formulario activo

[Ir a la sección en GitHub Pages](https://tusitio.github.io/ruta-del-archivo) ← *modifica este enlace según tu ruta real*

## 🧩 Integración

Este módulo forma parte del sistema general de Adopta un Sabio. Está conectado al mismo archivo de Google Sheets que la sección “Galería de Sabios”, pero guarda los datos en una hoja separada para facilitar su administración.

## 🔐 Seguridad y validación

- El formulario no se puede enviar si hay campos vacíos o el captcha no ha sido resuelto correctamente.
- Los datos se validan antes de enviarse.
- Se muestra confirmación visual tras el envío.

## 📁 Estructura de almacenamiento en Google Sheets

| Nombre | Testimonio | Fecha | Captcha | Estatus |
|--------|------------|-------|---------|---------|
| Texto  | Texto      | Fecha | ok      | pendiente |

## 🚀 Próximos pasos

- Integración con el **panel de administración** para aprobar o rechazar testimonios.
- Filtro para mostrar solo los aprobados en el carrusel.

---

📌 **Desarrollado por:** Daniel Jesús Carrillo Polanco  
🎨 **Diseño y código:** Adaptado en colaboración con IA – ChatGPT (OpenAI)

