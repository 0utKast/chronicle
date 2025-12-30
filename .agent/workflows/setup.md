---
description: Guía para inicializar y gestionar el proyecto Chronicle
---

# 🚀 Chronicle Workflow

Este flujo de trabajo define cómo operar en este proyecto manteniendo la memoria sincronizada.

## 1. Inicialización del Entorno
- // turbo
- Ejecutar `pip install fastapi uvicorn sqlalchemy`
- Verificar que el archivo `backend/database.db` se cree correctamente.

## 2. Actualización de Memoria
- Después de cada cambio significativo, actualizar el archivo `GEMINI.md`.
- Usar el comando `/conductor:setup` si se desea cambiar el stack tecnológico.

## 3. Ejecución de Servidores
- Recordar que el usuario prefiere iniciar los servidores manualmente.
- Backend: `uvicorn main:app --reload`
- Frontend: Abrir `index.html` o usar Live Server.
