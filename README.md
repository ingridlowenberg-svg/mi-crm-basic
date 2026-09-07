# Fluxio — Mi CRM Basic

Organizador de proyectos + CRM para estudios y equipos independientes. Escucha redes sociales por proyecto, convierte señales en leads y lleva cada cliente de la propuesta a la entrega en un mismo panel.

## Estructura

```
.
├── fluxio-landing.html   # Landing page de marketing
└── mi-crm/
    └── index.html        # Punto de entrada al panel (CRM)
```

## Desarrollo

Son archivos HTML estáticos sin build step. Para verlos localmente:

```bash
open fluxio-landing.html
```

Los CTAs de la landing ("Prueba gratis", "Crear cuenta gratis", etc.) enlazan a `mi-crm/index.html`, que hereda la identidad visual de Fluxio (tema oscuro, gradiente violeta-cian, tipografías Bricolage Grotesque y Plus Jakarta Sans).

## Stack

- HTML + CSS puro (sin framework)
- Google Fonts: Bricolage Grotesque, Plus Jakarta Sans, JetBrains Mono
