# 🌸 Paisaje de Cerezos al Atardecer - Museo Interactivo 3D

Una experiencia inmersiva en 3D de un hermoso paisaje japonés de cerezos (sakura) al atardecer, donde puedes explorar y encontrar 5 imágenes coleccionables.

## ✨ Características

### 🎨 Gráficos Avanzados
- **Cielo dinámico de atardecer** con colores cálidos (naranjas, rosas y rojos)
- **15 árboles de cerezo** detallados con flores rosadas
- **Sistema de partículas** con 500 pétalos cayendo en tiempo real
- **Terreno ondulado** con variación natural
- **2000 flores silvestres** distribuidas por el paisaje
- **Estanque reflectante** con nenúfares
- **Sendero de piedras** decorativo
- **Iluminación volumétrica** con múltiples fuentes de luz
- **Sombras en tiempo real** con mapa de sombras de alta calidad

### 🎮 Controles FPS (First Person)
- **W, A, S, D** - Moverse en todas direcciones
- **Mouse** - Mirar alrededor (primero haz click para activar)
- **Espacio** - Saltar
- **Shift** - Correr (velocidad doble)

### 🖼️ Sistema de Colección
- **5 imágenes** escondidas en pedestales dorados
- **Partículas brillantes** que indican la ubicación de cada imagen
- **UI en tiempo real** que muestra tu progreso
- **Efectos visuales** al recoger cada imagen
- **Mensaje de victoria** al completar la colección

## 📁 Estructura del Proyecto

```
cerezo-3d/
├── index.html          # Aplicación completa (HTML + CSS + JavaScript)
├── README.md           # Este archivo
└── images/             # Carpeta con las 5 imágenes
    ├── 1.png
    ├── 2.png
    ├── 3.png
    ├── 4.png
    └── 5.png
```

## 🚀 Cómo Ejecutar

### Opción 1: Servidor HTTP Simple (Recomendado)

```bash
cd /workspace/cerezo-3d
python3 -m http.server 8000
```

Luego abre tu navegador en: **http://localhost:8000**

### Opción 2: Usando Node.js

```bash
cd /workspace/cerezo-3d
npx serve
```

### Opción 3: VS Code Live Server

Si usas VS Code:
1. Instala la extensión "Live Server"
2. Haz click derecho en `index.html`
3. Selecciona "Open with Live Server"

## 🛠️ Tecnologías Utilizadas

- **Three.js** (v0.160.0) - Motor 3D profesional
- **PointerLockControls** - Controles tipo FPS
- **Sky Shader** - Cielo atmosférico realista
- **WebGL** - Renderizado GPU acelerado
- **ES6 Modules** - JavaScript moderno

## 🎯 Objetivos del Juego

1. Explora el hermoso paisaje de cerezos
2. Encuentra los 5 pedestales con imágenes
3. Acércate a cada pedestal (distancia < 3 unidades)
4. ¡Colecciona todas las imágenes!
5. Disfruta del mensaje de victoria

## 💡 Consejos

- Las imágenes están distribuidas por todo el mapa
- Cada pedestal tiene partículas doradas brillantes que lo delatan
- Usa **Shift** para moverte más rápido
- El estanque está al oeste (-X), los árboles principales al norte (-Z)
- Puedes saltar para tener mejor perspectiva

## 🌅 Detalles Atmosféricos

- **Hora del día**: Atardecer (sol bajo en el horizonte)
- **Colores dominantes**: Rosa (#ffb7c5), Naranja (#ffa07a), Rojo suave (#ff6b6b)
- **Niebla**: Ligera niebla rosa para profundidad
- **Pétalos**: 500 partículas animadas cayendo constantemente
- **Reflejos**: Estanque con material metálico que refleja el cielo

## 📊 Rendimiento

- **Antialiasing**: Activado para bordes suaves
- **Shadow Map**: 2048x2048 para sombras de alta calidad
- **Tone Mapping**: ACES Filmic para colores cinematográficos
- **FPS objetivo**: 60 FPS en hardware moderno

## 🎨 Paleta de Colores

```
Cielo:        #ff6b6b → #ffa07a
Cerezos:      #ffb7c5, #ff69b4, #ffc0cb
Troncos:      #4a3728
Hierba:       #2d5016
Flores suelo: #ffb6c1, #ffffff, #ff1493
Agua:         #4a90a4
Oro (marcos): #d4af37
```

## 🔧 Personalización

Puedes modificar fácilmente:
- Número de árboles en `treePositions`
- Cantidad de pétalos en `petalCount`
- Posiciones de las imágenes en `positions`
- Colores del atardecer en `createSky()`
- Velocidad de movimiento en `speed`

## 📱 Compatibilidad

- ✅ Chrome/Edge (recomendado)
- ✅ Firefox
- ✅ Safari
- ⚠️ Requiere WebGL 2.0
- ⚠️ Mejor experiencia con tarjeta gráfica dedicada

## 🎮 Experiencia Similar a Videojuego

Esta aplicación web ofrece una experiencia comparable a videojuegos indie gracias a:
- Movimiento fluido en primera persona
- Mundo abierto explorable (400x400 unidades)
- Elementos interactivos con feedback visual
- Atmósfera inmersiva con partículas y lighting
- Objetivo claro (colección de 5 imágenes)

¡Disfruta del paseo bajo los cerezos! 🌸
