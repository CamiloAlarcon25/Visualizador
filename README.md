# 🧠 Plataforma Interactiva de Casos Clínicos (ACV & Parkinson)

Una aplicación web interactiva y responsiva diseñada como herramienta educativa y de apoyo clínico. Permite visualizar modelos anatómicos en 3D del cerebro humano en tiempo real, vinculados dinámicamente con historiales clínicos y material teórico sobre el Accidente Cerebrovascular (ACV) y la Enfermedad de Parkinson.

## 🚀 Características Principales

*   **Visualización 3D Dinámica:** Integración de modelos interactivos (`.glb`) mediante la librería `<model-viewer>` de Google, permitiendo rotación, control de cámara y adaptabilidad táctil.
*   **Interactividad basada en Pestañas:** Sistema reactivo programado en JavaScript nativo que conmuta el modelo 3D, los encabezados y el caso de estudio sin necesidad de recargar la página.
*   **Diseño Totalmente Responsivo (Mobile-First y PC):** Interfaz optimizada para una navegación fluida en computadoras de escritorio y corregida específicamente para evitar desbordes y zooms innecesarios en pantallas de dispositivos móviles (iOS y Android).
*   **Contenido Estructurado:** Tarjetas de información médica visuales y descriptivas que detallan causas, síntomas (motores y no motores) y patologías celulares asociadas.

## 🛠️ Tecnologías Utilizadas

*   **HTML5:** Estructuración semántica de la plataforma.
*   **CSS3:** Diseño personalizado, variables globales (`:root`), transiciones y *Media Queries* avanzadas para la adaptabilidad móvil (`vw`/`vh`).
*   **JavaScript (Vanilla):** Lógica del lado del cliente para la manipulación dinámica del DOM y el intercambio de estados de la interfaz.
*   **Model-Viewer (Google):** Componente web nativo para el renderizado tridimensional compatible con WebXR.

## 📂 Estructura del Proyecto

```text
├── index.html          # Código fuente principal (UI, Estilos y Lógica)
├── cerebro.glb         # Modelo 3D para el caso de ACV
├── cerebro2.glb        # Modelo 3D para el caso de Parkinson
├── isquemico.png       # Imagen de apoyo para ACV Isquémico
├── hemorragico.png     # Imagen de apoyo para ACV Hemorrágico
├── mixto.png           # Imagen de apoyo para ACV Mixto
├── parkinson1.png      # Imagen de apoyo para Causa Neurológica de Parkinson
├── parkinson2.png      # Imagen de apoyo para Manifestaciones Motoras
└── parkinson3.png      # Imagen de apoyo para Patología Celular (Cuerpos de Lewy)

## Link para visualizar pagina web https://camiloalarcon25.github.io/Visualizador/
