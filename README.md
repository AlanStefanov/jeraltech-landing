# JERALTECH — Landing Page

Landing page oficial de **JERALTECH** (Software Factory · Staff Augmentation · Consultoría Ágil).

Sitio 100% estático: HTML + CSS + JavaScript vanilla, sin frameworks, sin build step y sin backend. Pensado para desplegar en Vercel en minutos.

## Estructura

```
.
├── index.html        # Markup y contenido de la landing
├── css/
│   └── styles.css    # Estilos (paleta de marca, layout, animaciones)
├── js/
│   └── main.js        # Menú mobile, scroll progress, reveal on scroll
├── assets/            # Logo, favicons, imagen OG
└── vercel.json        # Config mínima de Vercel (clean URLs, cache de assets)
```

## Identidad de marca

| Color                        | Hex       | Uso                              |
|------------------------------|-----------|-----------------------------------|
| Azul marino profundo          | `#061329` | Fondo principal                  |
| Azul eléctrico                | `#006BFF` | Acento primario / CTAs           |
| Cian tecnológico               | `#00D9F5` | Acento vivo / detalles           |
| Blanco frío                   | `#F4F7FC` | Texto                            |
| Azul profundo complementario  | `#123D8D` | Degradados                       |

Tipografía: **Space Grotesk** (títulos) + **Inter** (texto).

## Desarrollo local

No requiere instalación de dependencias. Alcanza con servir los archivos estáticos:

```bash
npx serve .
# o
python3 -m http.server 8080
```

## Despliegue (Vercel)

Este proyecto se despliega mediante la **integración nativa de Vercel con GitHub**:

1. Entrar a [vercel.com/new](https://vercel.com/new) e importar el repo `AlanStefanov/jeraltech-landing`.
2. Framework preset: **Other** (sitio estático, sin build command, output directory = raíz `.`).
3. Deploy.

A partir de ahí, **cada push a `main` dispara un deploy de producción automático**, y cada Pull Request genera un Preview Deployment propio. No se requieren tokens ni GitHub Actions adicionales.

## Contacto

WhatsApp Business: [+54 9 221 221-9756](https://wa.me/5492212219756)
