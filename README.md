# 📔 Chronicle - Personal Task Orchestrator

Chronicle es una aplicación de demostración diseñada para explorar y documentar el funcionamiento del sistema de **Memoria Persistente Chronicle** dentro del entorno de IA **Antigravity**.

Este proyecto no es solo un gestor de tareas; es un experimento vivo sobre cómo una IA puede mantener el contexto, las decisiones de diseño y el progreso a lo largo de múltiples sesiones y días, utilizando archivos de memoria estructurada (como `GEMINI.md`) y flujos de trabajo personalizados.

## 🚀 Características Principales

- **Gestión de Tareas Inteligente:** Creación y gestión de tareas con un enfoque en la orquestación.
- **Interfaz Premium:** Diseño moderno basado en **Glassmorphism**, con animaciones suaves y una estética visual de primer nivel utilizando CSS puro.
- **Backend Moderno:** Construido con **FastAPI** para una respuesta rápida y documentación automática.
- **Memoria Persistente:** Utiliza el sistema Chronicle para asegurar que el asistente IA (Antigravity) siempre sepa exactamente en qué punto del proyecto se encuentra.

## 🛠️ Stack Tecnológico

- **Frontend:** HTML5, JavaScript Vanilla, CSS3 (Custom HSL Palettes).
- **Backend:** Python 3.x, FastAPI.
- **Base de Datos:** SQLite con SQLAlchemy.
- **Entorno de IA:** Antigravity (Powered by Google DeepMind).

## 📂 Estructura del Proyecto

- `/backend`: Servidor FastAPI y lógica de base de datos.
- `/frontend`: Interfaz de usuario, estilos y lógica del cliente.
- `/docs`: Documentación adicional y recursos.
- `GEMINI.md`: El "Cerebro" del proyecto, donde se guarda la memoria persistente de Chronicle.

## 🔧 Instalación y Uso

1. **Requisitos:** Tener instalado Python 3.x.
2. **Dependencias:**
   ```bash
   pip install -r requirements.txt
   ```
3. **Ejecución:**
   Como parte de las reglas del proyecto, los servidores se inician manualmente en terminales externas:
   - **Backend:** `python backend/main.py`
   - **Frontend:** Abrir `frontend/index.html` o usar un servidor local.

## 🧠 Sobre el Sistema Chronicle

Chronicle permite que Antigravity lea y escriba en archivos específicos para "recordar" detalles cruciales del desarrollo. Este repositorio sirve como ejemplo de cómo estructurar proyectos para que sean amigables con agentes de IA autónomos.

---
*Desarrollado en colaboración con Antigravity.*
