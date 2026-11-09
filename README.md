# Bocetos Interactivos · Industrias Mazzei

Carpeta de bocetos interactivos de alta fidelidad para el nuevo sitio web de **Industrias Mazzei** (fabricación metalmecánica, mecanizado CNC, tornería pesada y soldadura industrial con más de 40 años de trayectoria).

## 🌐 Enlace Público en Vivo (Demo Online)

Puedes acceder a la versión desplegada y probarla directamente en tu móvil o navegador de escritorio en:

👉 **[https://raulrescobar.github.io/mazzei-boceto/](https://raulrescobar.github.io/mazzei-boceto/)**

---

## 📁 Archivos para abrir en el navegador

Puedes abrir cualquiera de estos archivos localmente haciendo doble clic sobre ellos en Chrome, Edge o Safari:

1. **`index.html` (o `narrativa.html`)** — **Propuesta Flagship Principal**:
   - **Theme Claro Industrial:** Fondo blanco nítido (`#FFFFFF`, `#F8FAFC`), azul corporativo Mazzei (`#074B85`, `#0270C7`) y grises metálicos de acero (`#0F172A`, `#334155`, `#CBD5E1`). *Cero uso de colores naranjas ajenos a la marca*.
   - **Activos 100% Reales:** Integración de las 20 fotografías reales del taller propio, maquinaria y clientes del sitio actual (`img/`).
   - **Hero con Tilt 3D:** Tarjetas interactivas con perspectiva tridimensional y efecto de brillo (*cursor shine*) reactivo al movimiento del ratón.
   - **Matriz de Servicios Técnicos:** 9 áreas operativas reales (Torno CNC, Soldadura Calificada TIG/MIG, Oxicorte y Plasma, Tornería Pesada hasta 3m, Fabricación según plano o muestra, Plegado CNC, Troquelado, Corte con Guillotina y Reconstrucción de Componentes).
   - **Parque de Maquinaria:** Especificaciones de capacidades máximas (volteo de 800 mm, longitud entre puntos de 3000 mm, corte por plasma de alta definición).
   - **Selector de Materiales:** Guía interactiva de aleaciones (AISI 4140 bonificado, AISI 1045, AISI 304/316 inoxidable y Bronce fosfórico SAE 660).
   - **Protocolo de Paradas de Planta 24/7:** Stepper interactivo de 4 pasos para contingencias mecánicas de alta criticidad en molinos, silos y transporte.
   - **Cotizador Rápido RFQ:** Generador de solicitud de presupuesto con selección de servicio, adjunto de planos y despacho automático a WhatsApp con datos técnicos pre-llenados.
   - **Schema.org JSON-LD:** Marcado de datos estructurados para posicionamiento SEO local B2B y motores de IA (AEO/GEO).

2. **`conceptos-visuales.html`** — **Laboratorio de Conceptos Visuales & Motion**:
   - **Pestaña 1 (🔬 Metrología Láser ±0.01 mm):** Simulación de banco de medición óptico CMM en torno CNC, con retícula animada, lectura digital de coordenadas en vivo (ejes X, Z y Ø) y selector de fichas técnicas de aleaciones mecánicas (dureza HRC, resistencia a tracción y norma ASTM).
   - **Pestaña 2 (⚡ Simulador Parada 24/7):** Calculadora interactiva del costo financiero de una línea de producción detenida por hora según el sector (Central Azucarero, Silos, Plantas Cerámicas) vs el ahorro de la respuesta inmediata Mazzei. Botón directo de despacho de emergencia a WhatsApp.
   - **Pestaña 3 (🔄 Escáner Antes / Después):** Comparador de cortina deslizante (*split slider*) interactivo entre una pieza industrial desgastada en planta vs la pieza recuperada por Mazzei con tolerancias nominales y endurecimiento superficial.

---

## 🛠️ Tecnologías Empleadas en el Boceto

- **HTML5 Semántico:** Diseñado con estándares accesibles y estructura preparada para componentes de **Astro**.
- **Tailwind CSS (JIT vía CDN):** Paleta customizada con tokens corporativos `mazzei` y `metal`.
- **Vanilla JavaScript:** Micro-interacciones de cero dependencias externas para garantizar 60 FPS en móviles y tiempos de carga instantáneos (&lt; 0.5s).
- **Optimización de Imágenes:** Imágenes reales comprimidas y organizadas en `img/`.

---

## 🚀 Despliegue en GitHub Pages

Este boceto está sincronizado con el repositorio público [`RaulREscobar/mazzei-boceto`](https://github.com/RaulREscobar/mazzei-boceto) y publicado automáticamente en GitHub Pages.
