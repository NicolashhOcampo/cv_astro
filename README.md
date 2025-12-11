# 📄 cv_astro – Generador de CV basado en `resume.json`

Este proyecto permite generar un **Currículum Vitae** automáticamente a partir de un archivo `resume.json`.  
Solo tenés que editar tu información en ese archivo, y el sistema genera un CV listo para imprimir utilizando **Astro**.

---

## 🚀 Características

- Construido con **Astro**.
- Generación automática del CV a partir de un único archivo JSON.
- Diseño limpio y optimizado para impresión.
- Separación completa entre datos y presentación.

---

## 🗂️ Estructura del Proyecto

```
cv_astro/
├── src/
│   ├── components/
│   ├── layouts/
│   ├── pages/
│   └── resume.json   ← Archivo editable con tu información
├── public/
├── astro.config.mjs
├── package.json
└── README.md
```

---

## ✏️ Cómo usar el proyecto

### 1. Clonar el repositorio

```bash
git clone https://github.com/tu-usuario/cv_astro.git
cd cv_astro
```

### 2. Instalar dependencias

```bash
npm install
```

### 3. Editar `resume.json`

Modificá tus datos personales, educación, experiencia, habilidades y proyectos.  
El sitio se actualizará automáticamente.

### 4. Ejecutar el proyecto

```bash
npm run dev
```

Luego abrí:

```
http://localhost:4321
```

---

## 🖨️ Generar la versión imprimible

La vista está optimizada para impresión.  
Desde el navegador presioná:

```
Ctrl + P
```

y elegí **Guardar como PDF**.

---



