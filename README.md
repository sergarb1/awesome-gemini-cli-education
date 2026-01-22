# 🤖 Multi-Agent Orchestrator Framework

[English](#english) | [Castellano](#castellano)

---

<a name="english"></a>
## 🇬🇧 English: System Overview

This repository contains the core configuration for a **Multi-Agent Orchestration System** designed for the Gemini CLI. It transforms a standard LLM interaction into a collaborative workflow between specialized agents.

### 🧩 Core Components
- **`.gemini/instructions.md`**: The master orchestrator that defines global rules, quality standards, and agent interaction protocols.
- **`.gemini/agents/`**: A library of specialized personas (SME, Architect, Visual Artist, etc.) with unique skills and mandates.
- **`GEMINI.md`**: A root-level trigger that ensures Gemini automatically loads the project context upon initialization.

### 🚀 How it Works
1. **Auto-Load:** When you open this folder with the Gemini CLI, the system reads `GEMINI.md` and `.gemini/instructions.md`.
2. **Specialization:** Each agent in the `agents/` folder is ready to be invoked or act according to the global instructions.
3. **Collaboration:** The agents don't just act alone; they are programmed to review and enhance each other's work (e.g., the *Visual Artist* beautifies what the *Architect* structures).

---

<a name="castellano"></a>
## 🇪🇸 Castellano: Resumen del Sistema

Este repositorio contiene la configuración central de un **Sistema de Orquestación Multi-Agente** diseñado para el CLI de Gemini. Transforma una interacción estándar con un LLM en un flujo de trabajo colaborativo entre agentes especializados.

### 🧩 Componentes Principales
- **`.gemini/instructions.md`**: El orquestador maestro que define las reglas globales, los estándares de calidad y los protocolos de interacción entre agentes.
- **`.gemini/agents/`**: Una biblioteca de perfiles especializados (SME, Arquitecto, Artista Visual, etc.) con habilidades y mandatos únicos.
- **`GEMINI.md`**: Un activador a nivel de raíz que asegura que Gemini cargue automáticamente el contexto del proyecto al iniciar.

### 🚀 Cómo Funciona
1. **Carga Automática:** Al abrir esta carpeta con el CLI de Gemini, el sistema lee `GEMINI.md` y `.gemini/instructions.md`.
2. **Especialización:** Cada agente en la carpeta `agents/` está listo para ser invocado o actuar según las instrucciones globales.
3. **Colaboración:** Los agentes no solo actúan solos; están programados para revisar y mejorar el trabajo de los demás (ej. el *Visual Artist* embellece lo que el *Architect* estructura).

---
*Framework developed for advanced educational automation*
