# David García — Biodecodificador

Landing page profesional para David García, especialista en comprensión del síntoma.

## Descripción

Sitio web estático diseñado para presentar los servicios de biodecodificación de David García, incluyendo sesiones individuales, trabajo con deportistas, talleres y monográficos.

## Características

- **Diseño responsive**: Adaptado para dispositivos móviles y desktop
- **Tipografía elegante**: Uso de Playfair Display para títulos e Inter para el cuerpo
- **Paleta de colores profesional**: Tonos tierra con acentos en azul aciano
- **Navegación por anclas**: Fácil acceso a todas las secciones
- **Optimizado para SEO**: Meta tags y estructura semántica

## Estructura del proyecto

```
david-garcia-web/
├── index.html          # Página principal
├── style.css           # Estilos CSS
└── README.md          # Este archivo
```

## Tecnologías utilizadas

- HTML5
- CSS3
- Google Fonts (Inter y Playfair Display)

## Cómo usar

### Opción 1: Abrir directamente
Simplemente abre el archivo `index.html` en tu navegador web.

### Opción 2: Servidor local con Python
```bash
# Python 3
python3 -m http.server 8000

# Luego visita http://localhost:8000
```

### Opción 3: Servidor local con Node.js
```bash
# Instalar http-server globalmente
npm install -g http-server

# Ejecutar en el directorio del proyecto
http-server -p 8000

# Luego visita http://localhost:8000
```

## Secciones de la página

1. **Hero**: Presentación principal con frase destacada
2. **Método**: Explicación del enfoque ciencia + espiritualidad
3. **Sesiones individuales**: Descripción del servicio principal
4. **Deportistas**: Servicios especializados para atletas
5. **Talleres y conferencias**: Formación grupal
6. **Monográficos**: Investigaciones temáticas
7. **Contacto**: Información de contacto

## Personalización

### Cambiar colores
Edita las variables CSS en `style.css`:
```css
:root{
  --bg: #ffffff;
  --text: #1a1a1a;
  --accent: #6495ed;
  /* ... más variables */
}
```

### Modificar contenido
Edita el archivo `index.html` directamente. El contenido está organizado por secciones con IDs claros.

### Ajustar tipografía
Las fuentes se cargan desde Google Fonts. Para cambiarlas, modifica la línea de importación en `style.css`.

## Despliegue

### GitHub Pages
1. Sube los archivos a un repositorio de GitHub
2. Ve a Settings > Pages
3. Selecciona la rama main como fuente
4. Tu sitio estará disponible en `https://tu-usuario.github.io/nombre-repo`

### Netlify
1. Arrastra la carpeta del proyecto a [Netlify Drop](https://app.netlify.com/drop)
2. Tu sitio estará en línea en segundos

### Vercel
```bash
# Instalar Vercel CLI
npm i -g vercel

# Desplegar
vercel
```

## Información de contacto (en el sitio)

- **Email**: contacto@emocion.com
- **WhatsApp**: +54 9 0000 0000 00

## Licencia

Proyecto personal de David García. Todos los derechos reservados.

## Notas

- El sitio es completamente estático, no requiere backend
- No hay dependencias de JavaScript
- Compatible con todos los navegadores modernos
- Optimizado para rendimiento y accesibilidad
