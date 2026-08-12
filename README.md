# Simulador de Reactor Agitado 3D — Ingeniería Química

Simulador interactivo 3D para la enseñanza y análisis de operaciones unitarias de agitación y mezclado de líquidos en reactores químicos, basado en las correlaciones empíricas y teoría del **Capítulo 9 de McCabe, Smith & Harriott (*Operaciones Unitarias en Ingeniería Química*)**.

---

## 🚀 Características Principales

- **Simulación Hidrodinámica 3D**: Renderizado interactivo en tiempo real con Three.js WebGL.
- **Gráfico Rushton Log-Log ($N_p$ vs $Re$)**: Curva adimensional interactiva con ubicación del punto de operación actual (Régimen Laminar, Transicional y Turbulento).
- **Perfil de Velocidad y Sonda 3D**: Gráfico del perfil radial $v(r)$ con desglose vectorial ($v, v_r, v_z, v_\theta$) en puntos seleccionados (Punta del aspa, Zona media, Pared, Eje).
- **Vórtice Libre 3D**: Deformación parabólica de la superficie del líquido al operar sin deflectores (bafles = 0) a altas RPM.
- **Zonas Muertas ("Efecto Dona")**: Visualización 3D de los anillos toroidales estancados característicos por encima y por debajo del impulsor.
- **Audio Sintetizado de Motor**: Sonido de motor dinámico accionado mediante Web Audio API.
- **Exportación de Datos**: Generación de reportes técnicos de laboratorio e impresión, y descarga de datos en CSV.
- **Diseño Responsivo Multiplataforma**: Adaptado para smartphones, tablets, laptops y pantallas de escritorio.

---

## 🛠 Tecnologías Utilizadas

- **Core**: HTML5 / CSS3 (Estética Glassmorphism Cyberpunk CAD)
- **Visualización 3D**: Three.js r128 (WebGL & OrbitControls)
- **Gráficos 2D**: HTML5 Canvas API
- **Audio**: Web Audio API (Sintetizador procedural)

---

## 📋 Uso Local

1. Clona el repositorio o descarga los archivos.
2. Abre `index.html` o `simulador_reactor_agitado_9.html` en cualquier navegador web moderno (Chrome, Edge, Firefox, Safari).
3. ¡No requiere dependencias ni servidores backend complejos!
