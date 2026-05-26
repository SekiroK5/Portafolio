# 🌟 Portafolio Profesional — Noé Chavero Martínez

> **Práctica 1 — Integradora de Desarrollo Web**  
> Personalización y Publicación Profesional de un Sitio Web con Git y GitHub

---

## 👨‍💻 Nombre del estudiante

**Noé Chavero Martínez**  
Técnico Superior Universitario en Desarrollo de Software Multiplataforma  
Estudiante de Ingeniería en Desarrollo y Gestión de Software  
📍 Dolores Hidalgo C.I.N., Guanajuato, México  
📧 [noe.ch.mtz97@gmail.com](mailto:noe.ch.mtz97@gmail.com)  
🐙 [github.com/SekiroK5](https://github.com/SekiroK5)

---

## 🎯 Objetivo de la práctica

Personalizar una plantilla web profesional utilizando **Git y GitHub**, adaptándola a un perfil profesional real. Se aprende el flujo de trabajo profesional de desarrollo web: clonar un repositorio, analizar su estructura, modificar el código, documentar los cambios y publicar en un repositorio remoto propio.

---

## 🔗 Repositorio base clonado

```bash
git clone https://github.com/DaneshCode/Portfolio-Website.git
```

**Repositorio original:** [DaneshCode/Portfolio-Website](https://github.com/DaneshCode/Portfolio-Website)  
**Repositorio personalizado:** [SekiroK5/Portafolio](https://github.com/SekiroK5/Portafolio)

---

## 🛠️ Tecnologías utilizadas

| Tecnología | Uso |
|-----------|-----|
| HTML5 | Estructura del sitio |
| CSS3 | Estilos y animaciones |
| JavaScript | Lógica e interactividad |
| Swiper.js | Slider del portafolio |
| AOS Library | Animaciones al hacer scroll |
| Unicons | Iconografía |
| Git | Control de versiones |
| GitHub | Repositorio remoto |

---

## ✏️ Cambios realizados

### 🔤 Información personal
- Nombre actualizado: **Danesh Khodadad** → **Noé Chavero Martínez**
- Título profesional: *Frontend Developer* → **Fullstack Developer / Software Engineer**
- Texto animado: `"Fullstack Developer"`, `"Software Engineer"`, `"Backend Developer"`, `"DB Architect"`
- Descripción: actualizada al perfil real del desarrollador
- Datos de contacto: teléfono real, email real, ubicación (Dolores Hidalgo, Guanajuato)

### 🎨 Colores y estilos
- Color principal: `--hue-color: 250` (morado) → `--hue-color: 230` (**azul moderno**)
- Barras de habilidades actualizadas con porcentajes reales del CV

### 👤 Sección About Me
Bloque de código personalizado con información real:
```js
const Noé = {
  location: "Dolores Hidalgo, Guanajuato, México",
  degree: "Software Dev. & Management Engineering",
  code: ["Angular", "TypeScript", "Laravel", "PostgreSQL", "Node.js"],
  askMeAbout: ["web dev", "microservices", "databases", "REST APIs"],
  currentFocus: "Building scalable and efficient systems",
  funFact: "Clean code is not written for machines, it's written for humans"
}
```
Estadísticas: **2+ años de experiencia**, **3+ empresas**, **10+ proyectos**

### 🛠️ Sección Skills
**Frontend & Backend:**
- Angular v18/19 — 85%
- TypeScript — 80%
- Laravel — 75%
- Node.js — 70%

**Databases & Tools:**
- PostgreSQL — 85%
- Git & GitHub — 80%
- Docker — 65%

### 🎓 Sección Qualification
**Educación:**
- Software Dev. & Management Engineering — UTNG (2025 - Present)
- TSU Multiplatform Software Dev. — UTNG (2023 - 2025)

**Experiencia:**
- Fullstack Developer — LKS BaaS / Karaoke IA Web (May 2025 - Sep 2025)
- Database Leader — LKS BaaS / Finner Platform (Jan 2025 - May 2025)
- Backend Developer — Library System UTNG (May 2024 - Aug 2024)

### 💼 Sección Services
- **Fullstack Development:** Angular 18 & Laravel, REST APIs seguras con JWT/RBAC, Canvas API
- **Database Architecture:** PostgreSQL, SOA, normalización 3FN, triggers y stored procedures

### 🖼️ Sección Portfolio
- **Karaoke IA Web — LKS BaaS:** Plataforma B2B con Angular 18 & Laravel 10, 180+ clientes activos
- **Finner Platform — LKS BaaS:** Modelo relacional PostgreSQL 16 bajo arquitectura SOA
- **Library System — UTNG:** API REST segura con RBAC, desplegada en servidores cloud

### 🖼️ Imágenes
- Foto de perfil propia en el hero principal (Avatar.jpg)
- Imágenes del About, Portfolio y CTA reemplazadas por imágenes profesionales via Unsplash CDN

---

## 💻 Git — Comandos utilizados

```bash
# 1. Clonar el repositorio original
git clone https://github.com/DaneshCode/Portfolio-Website.git

# 2. Verificar estado de los archivos
git status

# 3. Agregar todos los cambios al área de staging
git add .

# 4. Crear un commit con mensaje descriptivo
git commit -m "Personalizacion completa del portafolio profesional - Noe Chavero Martinez"

# 5. Verificar el repositorio remoto actual
git remote -v

# 6. Eliminar la referencia remota original (DaneshCode)
git remote remove origin

# 7. Conectar con el repositorio remoto propio
git remote add origin https://github.com/SekiroK5/Portafolio.git

# 8. Renombrar la rama principal
git branch -M main

# 9. Subir el proyecto a GitHub
git push -u origin main

# Otros comandos utilizados en la práctica
git pull origin main   # Descargar cambios del remoto
git branch             # Ver ramas existentes
```

---

## 📁 Estructura del proyecto

```
Portfolio-Website/
├── index.html              # Página principal del portafolio
├── styles.css              # Estilos y variables CSS
├── main.js                 # Lógica JavaScript (nav, skills, swiper)
├── README.md               # Este archivo — documentación completa
└── assets/
    ├── img/
    │   ├── Avatar.jpg      # Foto de perfil personal
    │   ├── favicon.png     # Ícono del sitio
    │   └── blob.svg        # Forma del hero
    └── PDF/
        └── CV_Noe_Chavero.pdf  # Currículum Vitae
```

---

## 📸 Evidencias

### Sitio original (antes de personalizar)
<img width="1847" height="982" alt="Portafolio Original" src="https://github.com/user-attachments/assets/12650260-ae5d-42fc-b314-74e6f2aaa06c" />

---

### Sitio personalizado (resultado final)
<img width="1800" height="989" alt="Portafolio Personalizado" src="https://github.com/user-attachments/assets/92782566-0c7c-4f0e-9999-7fe48a00d9a6" />

---

### Repositorio clonado
<img width="1153" height="532" alt="Repositorio Clonado" src="https://github.com/user-attachments/assets/b3bfbaca-ab09-4a08-b38b-09a38ba8681f" />

---

## 🔗 URLs

| Recurso | URL |
|---------|-----|
| 🐙 Repositorio GitHub | [github.com/SekiroK5/Portafolio](https://github.com/SekiroK5/Portafolio) |
| 🌐 Sitio publicado (GitHub Pages) | `https://seirok5.github.io/Portafolio/` *(activar en Settings → Pages)* |

---

## 🚀 Características del sitio

- 🌙 Toggle modo oscuro / claro
- 📱 Diseño completamente responsivo
- ✨ Animaciones con AOS al hacer scroll
- ⌨️ Efecto de escritura animada (typewriter)
- 📊 Barras de habilidades con porcentajes reales
- 🎠 Slider de portafolio con Swiper.js
- 📬 Formulario de contacto
- 🔗 Links a redes sociales reales (LinkedIn, GitHub, Email)

---

*Práctica realizada como parte del curso de Desarrollo Web — Instituto Tecnológico*  
*Basado en la plantilla de [DaneshCode](https://github.com/DaneshCode/Portfolio-Website) — Personalizado por Noé Chavero Martínez*
