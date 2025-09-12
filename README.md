# 🕒 LuxTime - Tienda de Relojes de Lujo

Sitio web elegante para una tienda de relojes de lujo, con diseño responsivo y múltiples secciones informativas.

---

## 📋 Tabla de Contenidos

- [Descripción del Proyecto](#-descripción-del-proyecto)  
- [Características](#-características)  
- [Estructura del Sitio](#️-estructura-del-sitio)  
- [Tecnologías Utilizadas](#️-tecnologías-utilizadas)  
- [Instalación y Uso](#-instalación-y-uso)  
- [Estructura de Archivos](#-estructura-de-archivos)  
- [Personalización](#-personalización)  
- [Añadir Nuevas Imágenes](#-añadir-nuevas-imágenes)  
- [Despliegue](#-despliegue)  
- [Autor](#-autor)  
- [Licencia](#-licencia)

---

## 📖 Descripción del Proyecto

LuxTime es un sitio web elegante para una tienda de relojes de lujo ficticia. El proyecto incluye:

- Página principal con carrusel de imágenes y productos destacados  
- Sección de historia corporativa con línea de tiempo  
- Página de catálogo de productos  
- Formulario de contacto con validación  
---

## ✨ Características

- Diseño elegante y moderno con esquema de colores negro, blanco y dorado  
- Carrusel automático en la página principal con 5 imágenes  
- Grid de productos responsivo con efectos hover  
- Línea de tiempo interactiva para la historia corporativa  
- Formulario de contacto con validación visual  
- Navegación consistente en todas las páginas
---

## 🏗️ Estructura del Sitio

El sitio web consta de 4 páginas principales:

| Página | Descripción |
|--------|------------|
| **Inicio (index.html)** | Presentación con banner, productos destacados e historia corporativa |
| **Catálogo (catalogo.html)** | Listado completo de productos |
| **Historia (historia.html)** | Información histórica de la empresa con línea de tiempo y galería |
| **Contacto (contacto.html)** | Formulario de contacto e información de la empresa |

---

## 🛠️ Tecnologías Utilizadas

| Tecnología | Uso |
|------------|-----|
| HTML5 | Estructura semántica del contenido |
| CSS3 | Estilos y diseño responsivo |
| CSS Grid & Flexbox | Layouts modernos y adaptables |
| Animaciones CSS | Transiciones y efectos visuales |
---

## 💻 Instalación 

1. Clona el repositorio:
git clone https://github.com/kvinnxz/Proyecto_Pico_Kevin.git
2. Ingresa a la carpeta:
  
   cd Proyecto
   
3. Abre el archivo `index.html` en tu navegador.

## 📁 Estructura de Archivos
Proyecto_Pico_Kevin/
├── Codigos/
│   ├── index.html          # Página principal
│   ├── style.css           # Estilos principales
│   └── paginas/
│       ├── catalogo/
│       │   ├── catalogo.html  # Página de catálogo (pendiente)
│       │   └── [estilos.css]  # Estilos del catálogo (pendiente)
│       ├── historia/
│       │   ├── historia.html  # Página de historia
│       │   └── historia.css   # Estilos de la página de historia
│       └── contacto/
│           ├── contacto.html  # Página de contacto
│           └── contacto.css   # Estilos de la página de contacto
├── images/
│   ├── home/               # Imágenes para la página principal
│   ├── destacados/         # Imágenes de productos destacados
│   ├── historia/           # Imágenes para la sección de historia
│   └── videos/             # Videos corporativos
└── README.md               

## Modificar productos
Para actualizar los productos destacados, edita la sección en index.html:
<div class="card">
  <img src="/images/destacados/nuevo-reloj.png" alt="Nuevo Reloj">
  <h3>Nombre del Nuevo Reloj</h3>
  <p>$999 USD</p>
  <p>★★★★★</p>
  <a href="/paginas/catalogo/catalogo.html">
    <button>Ver Detalles</button>
  </a>
</div>

## 🖼️Añadir Nuevas Imágenes
Para agregar más imágenes al carrusel principal:

<div class="slide">
  <img src="/images/home/nueva-imagen.png" alt="Nueva Imagen">
  <div class="banner-content">
    <h1>Elegancia en Cada Segundo</h1>
    <a href="/paginas/catalogo/catalogo.html">
      <button>Ver Catálogo</button>
    </a>
  </div>
</div>
Asegúrate de ajustar la animación CSS para el número correcto de imágenes:

@keyframes slide {
  /* Ajustar los porcentajes según el número de imágenes */
}

## 🚀 Despliegue

# Netlify
👉 [Ver Portafolio en línea](https://68c3f63b090c244b250f1818--deluxe-dasik-f4e164.netlify.app/)

# 👨‍💻 Autor
Kevin - 👉 [kvinnxz](@kvinnxz/)

