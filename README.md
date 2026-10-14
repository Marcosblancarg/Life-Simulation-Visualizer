# Life Simulation Visualizer

Simulador básico de vida artificial y comportamiento de bandadas (algoritmo Boids) desarrollado en **HTML5 Canvas** y **JavaScript vanilla**.

El proyecto simula múltiples especies que interactúan entre sí con reglas de alineación, cohesión y separación, permitiendo visualizar patrones emergentes de movimiento orgánico en tiempo real.

---

## 🚀 Características

- **Multi-especie:** 4 especies simultáneas con parámetros independientes (velocidad, tamaño, radio de percepción, estela, etc.).
- **Algoritmo Boids optimizado:** Implementa partición espacial mediante una cuadrícula (*Spatial Grid*) para mantener un alto rendimiento con cientos de partículas.
- **Panel de control interactivo:** Ajuste dinámico de variables y colores por especie en tiempo real.
- **Compatible con Wallpaper Engine:** Incluye configuración `project.json` lista para usarse como fondo de pantalla animado interactivo.
- **Sin dependencias externas:** Funciona directamente abriendo `index.html` en cualquier navegador moderno.

---

## 🎮 Controles

- **`C`**: Muestra u oculta el panel de controles y parámetros.
- **`R`**: Reinicia la simulación con la configuración actual.

---

## 📁 Estructura

- `index.html`: Archivo principal con el código de la simulación, estilos y panel de control.
- `project.json`: Metadatos y definición de propiedades compatibles con Wallpaper Engine.
- `FINAL/`: Versión empaquetada/alternativa del proyecto.

