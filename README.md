# 🎨 Open Design Simplificado

## La guía definitiva en español para instalar Open Design paso a paso

Instala Open Design aunque NO seas programador.  
Sin tecnicismos. Sin dolores de cabeza.

---

## 🧠 ¿Qué es Open Design?

Open Design es una herramienta open source que permite crear:

- Interfaces
- Landing pages
- Dashboards
- Prototipos
- Experiencias visuales

usando inteligencia artificial con lenguaje natural.

Muchos la consideran una alternativa open source a Claude Design ya que tiene una interfaz similiar, también la mayoria de funciones y caracteristicas.

---

## ⚠️ Importante

Open Design NO incluye inteligencia artificial integrada.

Necesitas conectarlo con:
- Gemini CLI
- Claude Code
- u otros modelos compatibles.

En esta guía utilizaremos Gemini CLI porque es una de las opciones más simples para comenzar.

---

# 🛠️ Paso 1 — Instalar Node.js

Descarga Node.js aquí:

https://nodejs.org/

👉 Descarga la versión:
✅ LTS

---

# 🧩 Paso 2 — Instalar pnpm

Abre PowerShell como Administrador y pega esto:

```bash
npm install -g pnpm
```

---

# 📦 Paso 3 — Descargar Open Design

Repositorio oficial:

https://github.com/nexu-io/open-design

Descarga el ZIP y descomprímelo.

Ejemplo:

```txt
C:\open-design
```

---

# ⚙️ Paso 4 — Instalar dependencias

Dentro de la carpeta:

1. Haz clic derecho
2. “Abrir en Terminal”

Luego ejecuta:

```bash
pnpm install
```

---

# 🧠 Paso 5 — Instalar Gemini CLI

```bash
npm install -g @google/gemini-cli
```

---

# 🔑 Paso 6 — Obtener tu API Key

Ve a:

https://aistudio.google.com/

Genera tu API Key.

⚠️ No la compartas públicamente.

---

# 🤖 Paso 7 — Activar Gemini

En PowerShell escribe:

```bash
gemini
```

Selecciona:

✅ Trust Folder  
✅ Use Gemini API Key

Luego pega tu API Key.

---

# 🎨 Paso 8 — Encender Open Design

Dentro de la carpeta del proyecto:

```bash
pnpm tools-dev run web
```

---

# 🌐 Paso 9 — Abrir Open Design

Abre la URL local que aparecerá en pantalla.

Ejemplo:

```txt
http://localhost:3000
```

---

# 🔗 Paso 10 — Conectar Gemini CLI

Dentro de Open Design:

1. Busca “Local CLI”
2. Activa:
   ✅ Gemini CLI

Y listo 🚀

---

# ⚡ Tu primer prompt

```txt
Create a futuristic AI dashboard with dark mode and Apple-level minimalism.
```

---

# 🧠 ¿Por qué hice esta guía?

La mayoría de tutoriales de IA parecen hechos solo para desarrolladores.

Esta guía fue creada para:
- creadores,
- marketers,
- freelancers,
- diseñadores,
- emprendedores,
- y curiosos de IA.

Mi objetivo fue traducir lo complejo en simple.

---

# 👨‍🚀 Sobre el autor de la guía

Jonatan Correa • Consultor y Divulgador de IA • 2026
