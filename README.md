# PokéDebilidades 🔥⚡🌱

PokéDebilidades es una pequeña aplicación web **mobile-first** que permite consultar rápidamente:

- ✔️ Tipos de ataque **muy eficaces** contra un Pokémon  
- ✔️ Tipos **poco eficaces**  
- ✔️ Tipos **sin efecto**  
- ✔️ Imagen oficial del Pokémon  
- ✔️ Autocompletado mientras escribes  

La app obtiene los datos en tiempo real usando **PokéAPI** y está diseñada para usarse fácilmente desde móviles o como app instalada en la pantalla de inicio.

---

## 🎮 Cómo usar la aplicación

1. Accede a la app desde GitHub Pages:  
   👉 **https://olista94.github.io/PokeDebilidades/**
2. Escribe el nombre de un Pokémon (en inglés, ejemplo: *meowth*, *pikachu*, *charizard*…).
3. Selecciona una sugerencia o pulsa **Buscar**.
4. La app mostrará:
   - Los **tipos defensivos** del Pokémon  
   - Los ataques **muy eficaces** (x2, x4)  
   - Los ataques **poco eficaces** (x0.5, x0.25)  
   - Los ataques **sin efecto** (x0)  
   - La imagen oficial del Pokémon  

---

## 📱 Instalar como App en tu móvil

### **Android (Chrome)**  
1. Abre: https://olista94.github.io/PokeDebilidades/  
2. Pulsa menú (⋮)  
3. Elige **“Añadir a pantalla principal”** o **“Instalar app”**  
4. ¡Tendrás un icono como si fuera una app nativa!  

### **iPhone (Safari)**  
1. Abre la misma URL  
2. Toca el botón **Compartir**  
3. Selecciona **“Añadir a pantalla de inicio”**  
4. Confirma el nombre y listo  

Gracias al `manifest.json` y al icono incluido, el móvil mostrará un **icono personalizado**.

---

## 🚀 Despliegue con GitHub Pages

Este proyecto funciona sin servidor, únicamente con HTML, CSS y JavaScript.  
Por eso puede desplegarse muy fácilmente:

1. En GitHub, ve a **Settings → Pages**  
2. En **Source**, selecciona:  
   - *Deploy from a branch*  
   - Branch: `main`  
   - Folder: `/ (root)`  
3. Guarda la configuración  
4. GitHub generará la URL pública de la app

---

## 🧩 Estructura del proyecto
```
├── index.html # Aplicación principal
├── manifest.json # Manifest para PWA (permite icono y modo app)
├── icon-192.png # Icono de la aplicación
└── README.md # Este archivo
```

---

## 🛠️ Tecnologías utilizadas

- **HTML5 + CSS3** (diseño mobile-first)
- **JavaScript**
- **PokéAPI** → https://pokeapi.co/
- **GitHub Pages** para despliegue

---

## 📚 Créditos

- Datos e imágenes obtenidas de **PokéAPI**  
- Diseño inspirado en la estética clásica de Pokémon  
- Desarrollado por **@olista94**

---

## 🐱 Ejemplo rápido

Buscar: **Meowth**

La app mostrará:

- Tipos: *Normal*  
- Muy eficaz contra él: **Lucha (x2)**  
- Poco eficaz: **Roca, Acero (x0.5)**  
- Sin efecto: **Fantasma (x0)**  

---


¡Disfruta de tu Pokédex de debilidades!
