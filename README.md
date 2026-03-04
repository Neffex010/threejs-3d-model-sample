# 🚀 Visor 3D: Importación del Halcón Milenario con Three.js

Este proyecto es una práctica de renderizado web en 3D basada en el tutorial *"Añade un modelo 3D interactivo a tu sitio web // Tutorial de Three.js para principiantes"* del autor `dgreenheck`. 

El objetivo principal de este desarrollo es aprender a implementar el cargador moderno de Three.js para renderizar de forma interactiva el modelo del icónico **Halcón Milenario** de Star Wars.

## 📌 Datos Académicos
* **Institución:** Instituto Tecnológico de Pachuca
* **Carrera:** Ingeniería en Tecnologías de la Información y Comunicaciones (ITICS)
* **Materia:** Desarrollo de soluciones en ambientes virtuales
* **Alumno:** Luis Enrique Cabrera García

## 🌌 Descripción del Proyecto
A diferencia de los modelos FBX tradicionales, esta práctica se centra en el uso del formato **GLTF / GLB** (GL Transmission Format), considerado el "JPEG del 3D" por su alta compresión, eficiencia y rápida carga en navegadores web. 

La aplicación configura una escena completa de WebGL que incluye renderizado antialiasing, iluminación dinámica para resaltar los detalles metálicos de la nave y controles orbitales para que el usuario pueda inspeccionar el modelo desde cualquier ángulo.

## ✨ Características Principales
* **Carga Optimizada (GLTFLoader):** Implementación del cargador oficial de Three.js para formatos `.gltf` y `.glb`, permitiendo cargar la malla, materiales y texturas empaquetadas en un solo archivo ligero.
* **Iluminación de Escena:** Configuración de luces ambientales (`AmbientLight`) y direccionales (`DirectionalLight`) para darle volumen y realismo a la geometría de la nave.
* **Controles Orbitales 360°:** Integración de `OrbitControls` para permitir la interacción libre del usuario con el modelo espacial.
* **Renderizado Responsivo:** La cámara (`PerspectiveCamera`) y el lienzo de WebGL se ajustan dinámicamente si el usuario redimensiona la ventana del navegador.

## 🛠️ Tecnologías Utilizadas
* **Lenguajes:** HTML5, CSS3, JavaScript (Vanilla / ES6)
* **Librerías:** Three.js (WebGL)
* **Formatos 3D:** GLTF / GLB
* **Referencia:** [dgreenheck/threejs-gltf-import](https://github.com/dgreenheck/threejs-gltf-import)

## 🎮 Controles de Interacción
La nave se encuentra suspendida en el espacio virtual. Puedes interactuar con ella usando el ratón:
* **Clic Izquierdo + Arrastrar:** Rotar la cámara alrededor del Halcón Milenario.
* **Rueda del Ratón (Scroll):** Acercar (Zoom In) o alejar (Zoom Out) la vista.
* **Clic Derecho + Arrastrar:** Desplazar la cámara horizontal o verticalmente (Paneo).

## ⚙️ Instrucciones de Instalación y Uso
Para visualizar el modelo correctamente y evitar bloqueos por políticas de seguridad del navegador (CORS) al solicitar el archivo `.gltf`/`.glb`:

1. Clona este repositorio o descarga el código fuente.
2. Abre la carpeta del proyecto en tu editor de código (como Visual Studio Code).
3. Inicia un servidor web local (se recomienda la extensión **Live Server** de VS Code).
4. El proyecto se abrirá automáticamente en tu navegador por defecto (usualmente en `http://127.0.0.1:5500/`).
