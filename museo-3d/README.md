# 🏛️ Museo 3D Interactivo

Un museo virtual en 3D donde puedes explorar y encontrar 5 imágenes ocultas.

## 🎮 Cómo ejecutar la aplicación

### Opción 1: Usando Python (Recomendado)

```bash
cd museo-3d
python -m http.server 8000
```

Luego abre tu navegador en: `http://localhost:8000`

### Opción 2: Usando Node.js

Si tienes Node.js instalado, puedes usar `serve`:

```bash
npm install -g serve
cd museo-3d
serve .
```

### Opción 3: Usando PHP

```bash
cd museo-3d
php -S localhost:8000
```

## 🎯 Controles del juego

- **W, A, S, D** - Moverse hacia adelante, izquierda, atrás, derecha
- **Flechas del teclado o Mouse** - Mirar alrededor
- **Espacio** - Saltar
- **Click en la pantalla** - Activar/desactivar controles del mouse

## 🏆 Objetivo

Explora el museo y encuentra las **5 imágenes** escondidas en diferentes pedestales. Cada vez que te acerques a una imagen, se mostrará en pantalla y el contador se actualizará. ¡Encuéntralas todas para ganar!

## 📁 Estructura de archivos

```
museo-3d/
├── index.html          # Archivo principal de la aplicación
├── images/             # Carpeta con las 5 imágenes
│   ├── 1.png
│   ├── 2.png
│   ├── 3.png
│   ├── 4.png
│   └── 5.png
└── README.md           # Este archivo
```

## 🛠️ Tecnologías utilizadas

- **Three.js** - Biblioteca de gráficos 3D para WebGL
- **HTML5** - Estructura de la página
- **CSS3** - Estilos e interfaz de usuario
- **JavaScript ES6+** - Lógica del juego

## ✨ Características

- Entorno 3D interactivo tipo museo
- Sistema de movimiento en primera persona
- Detección de colisiones para recolectar imágenes
- Interfaz de usuario con contador de progreso
- Modal para visualizar las imágenes encontradas
- Mensaje de victoria al completar el objetivo
- Iluminación realista con sombras
- Elementos decorativos (columnas, pedestales, jarrones)

## 🔧 Requisitos

- Navegador web moderno con soporte para WebGL (Chrome, Firefox, Edge, Safari)
- Servidor HTTP local (para cargar correctamente los recursos)

## 📝 Notas

- Las imágenes deben estar en la carpeta `images/` con los nombres `1.png` hasta `5.png`
- El juego funciona mejor en pantallas grandes
- Se recomienda usar auriculares para una mejor experiencia inmersiva

---

¡Disfruta explorando el museo! 🎨🖼️
