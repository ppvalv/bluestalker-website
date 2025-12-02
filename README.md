# BlueStalker - Sitio Web Promocional

Sitio web promocional moderno y futurista para la plataforma BlueStalker, sistema de inteligencia pasiva mediante detección Bluetooth y WiFi.

## 🎨 Características del Diseño

### Estética Futurista
- **Paleta de colores**: Azul cian (#00d4ff) y azul oscuro con gradientes dinámicos
- **Tipografía**: 
  - Orbitron (headings) - Fuente futurista y tecnológica
  - Rajdhani (body) - Fuente moderna y legible
- **Efectos visuales**:
  - Glassmorphism con blur effects
  - Gradientes animados
  - Partículas interactivas
  - Efectos de brillo (glow)
  - Animaciones suaves y fluidas

### Fondo Animado
- Sistema de estrellas parpadeantes
- Grid overlay con movimiento
- Canvas de partículas interactivas que reaccionan al mouse
- Conexiones dinámicas entre partículas

### Secciones Principales

1. **Hero Section**
   - Radar animado con sweep effect
   - Puntos de dispositivos parpadeantes
   - Estadísticas animadas
   - Botones con efectos hover avanzados

2. **Features (Características)**
   - 6 tarjetas con iconos SVG personalizados
   - Efectos hover con elevación y brillo
   - Tags de tecnologías
   - Descripciones detalladas

3. **Screenshots (Capturas)**
   - Integración de imágenes del dashboard real
   - Overlay con información al hover
   - Efecto zoom en imágenes
   - Bordes con glow effect

4. **Use Cases (Casos de Uso)**
   - 6 casos de uso detallados
   - Numeración grande y estilizada
   - Listas de beneficios
   - Diseño card con efectos

5. **Technology (Tecnología)**
   - Stack tecnológico organizado por categorías
   - Diagrama de arquitectura interactivo
   - Iconos emoji para mejor visualización
   - Efectos hover en cada tecnología

6. **Future Capabilities (Capacidades Futuras)**
   - 6 capacidades planificadas
   - Badges de estado (En Desarrollo, Planificado, Investigación)
   - Sección de personalización
   - Iconos grandes y llamativos

7. **Download (Descargar)**
   - 4 plataformas disponibles
   - Código de instalación copiable
   - Botones de descarga
   - Requisitos del sistema

8. **Footer**
   - Enlaces organizados por categorías
   - Información de licencia
   - Advertencia de uso responsable

## 🚀 Tecnologías Utilizadas

- **HTML5**: Estructura semántica
- **CSS3**: 
  - Variables CSS
  - Flexbox y Grid
  - Animaciones y transiciones
  - Backdrop filters
  - Gradientes complejos
- **JavaScript ES6+**:
  - Clases y módulos
  - Canvas API para partículas
  - Intersection Observer
  - Event listeners optimizados

## 📁 Estructura de Archivos

```
bluestalker-website/
├── index.html          # Página principal
├── styles.css          # Estilos futuristas
├── script.js           # Funcionalidad interactiva
└── README.md           # Este archivo
```

## 🎯 Características Interactivas

### Animaciones JavaScript

1. **Sistema de Partículas**
   - 80 partículas flotantes
   - Interacción con el mouse
   - Conexiones dinámicas entre partículas cercanas
   - Efecto de repulsión al pasar el cursor

2. **Scroll Animations**
   - Aparición progresiva de elementos
   - Parallax effect en hero section
   - Navbar con efecto scroll
   - Activación de secciones en navegación

3. **Efectos Especiales**
   - Cursor personalizado con glow
   - Ripple effect en botones
   - Contador animado en estadísticas
   - Radar con sweep rotatorio
   - Dispositivos parpadeantes

4. **Funcionalidad**
   - Menú móvil hamburguesa
   - Smooth scroll a secciones
   - Copy to clipboard para código
   - Lazy loading de imágenes
   - Responsive design completo

## 📱 Responsive Design

El sitio es completamente responsive con breakpoints en:
- **Desktop**: > 1200px
- **Tablet**: 768px - 1200px
- **Mobile**: < 768px
- **Small Mobile**: < 480px

### Adaptaciones Móviles
- Menú hamburguesa
- Grid a una columna
- Tamaños de fuente ajustados
- Radar más pequeño
- Botones full-width
- Estadísticas en 2 columnas

## 🎨 Paleta de Colores

```css
--primary-blue: #00d4ff      /* Azul cian principal */
--secondary-blue: #0066ff    /* Azul secundario */
--dark-bg: #0a0e27          /* Fondo oscuro */
--darker-bg: #050811        /* Fondo más oscuro */
--accent-cyan: #00ffff      /* Acento cyan */
--accent-purple: #8b5cf6    /* Acento púrpura */
```

## 🔧 Personalización

### Cambiar Colores
Edita las variables CSS en `styles.css`:
```css
:root {
    --primary-blue: #TU_COLOR;
    --secondary-blue: #TU_COLOR;
    /* ... */
}
```

### Ajustar Animaciones
Modifica las velocidades en `styles.css`:
```css
--transition-fast: 0.2s ease;
--transition-normal: 0.3s ease;
--transition-slow: 0.5s ease;
```

### Cambiar Partículas
Edita en `script.js`:
```javascript
this.particleCount = 80;  // Número de partículas
this.mouse.radius = 150;  // Radio de interacción
```

## 🌐 Integración con Proyecto Real

El sitio integra las imágenes reales del proyecto BlueStalker:
- `../full_dashboard.png` - Dashboard completo
- `../BLEDevicesSection.png` - Sección BLE
- `../WifiDevicesSection.png` - Sección WiFi

Las rutas son relativas a la carpeta `bluestalker-website`.

## 📊 SEO y Accesibilidad

- Meta tags optimizados
- Títulos descriptivos
- Estructura semántica HTML5
- Alt text en imágenes
- Contraste de colores accesible
- Navegación por teclado

## 🚀 Cómo Usar

1. **Abrir directamente**:
   ```bash
   cd bluestalker-website
   open index.html  # macOS
   xdg-open index.html  # Linux
   start index.html  # Windows
   ```

2. **Con servidor local**:
   ```bash
   cd bluestalker-website
   python -m http.server 8080
   # Visita http://localhost:8080
   ```

3. **Con Live Server** (VS Code):
   - Instala extensión "Live Server"
   - Click derecho en `index.html`
   - "Open with Live Server"

## 🎯 Casos de Uso Destacados

El sitio presenta 6 casos de uso principales:

1. **Seguridad Personal** - Detección de seguimiento
2. **Análisis de Tráfico** - Estudio de patrones
3. **Investigación de Seguridad** - Pentesting
4. **Control de Acceso** - Identificación automática
5. **Wardriving Avanzado** - Mapeo de dispositivos
6. **IoT y Smart Home** - Monitoreo de red

## 🔮 Capacidades Futuras Destacadas

1. **Detección Multi-Frecuencia** - Sub-GHz, 5GHz, Zigbee, LoRa
2. **Detección de Jammers** - Análisis de espectro
3. **Machine Learning** - Predicción de patrones
4. **Red Distribuida** - Triangulación precisa
5. **Análisis de Seguridad** - Auditorías avanzadas
6. **Analytics Avanzado** - Visualización 3D

## 📝 Notas de Desarrollo

- Todas las animaciones usan `requestAnimationFrame` para mejor performance
- Los eventos de scroll están debounced
- Las imágenes usan lazy loading
- El código está modularizado en clases
- Compatible con navegadores modernos (Chrome, Firefox, Safari, Edge)

## 🎨 Iconografía

El sitio usa:
- **SVG inline** para iconos de características
- **Emoji** para iconos de tecnología y futuro
- **Símbolos Unicode** para detalles (◉, ✓, ▸)

## ⚡ Performance

Optimizaciones implementadas:
- CSS minificado en producción (recomendado)
- JavaScript modular y eficiente
- Animaciones con GPU acceleration
- Lazy loading de imágenes
- Debouncing de eventos
- Intersection Observer para animaciones

## 📄 Licencia

Este sitio web promocional está bajo la misma licencia MIT que el proyecto BlueStalker.

## 🤝 Contribuciones

Para mejorar el sitio:
1. Edita los archivos HTML/CSS/JS
2. Prueba en diferentes navegadores
3. Verifica responsive design
4. Optimiza performance

---

**Desarrollado con 💙 para BlueStalker**

*Sistema de Inteligencia Pasiva Bluetooth*
