# Pixel Taller

Portafolio y páginas de demostración para vender sitios web a negocios locales en CDMX.

## Estructura

```
index.html               Portafolio de Pixel Taller (página principal)
demos/dental/            Demo de clínica dental: agenda por WhatsApp, precios, guía de blanqueamiento
demos/restaurante/       Demo de restaurante: menú del día automático, carta, reservaciones
demos/taller/            Demo de taller mecánico: servicios, calendario de verificación
```

Cada página es un solo archivo HTML con su CSS y JavaScript dentro. No necesita instalar nada ni compilar.

## Verlo en tu compu

Abre `index.html` con doble clic, o levanta un servidor local:

```bash
python -m http.server 8000
```

y entra a http://localhost:8000

## Publicación

El sitio se publica con GitHub Pages desde la rama `main`. Cada `git push` actualiza la página en línea.

## Pendientes

- [ ] Cambiar el número de WhatsApp `55 0000 0000` por el real en `index.html`
- [ ] Hacer una demo personalizada para cada cliente que diga que sí. Guárdala fuera del repo o publícala solo con su permiso.
- [ ] Agregar fotos reales cuando un cliente las mande

## Privado

`kit-de-ventas.md` (contactos, precios y mensajes) está en `.gitignore` y nunca se sube.
