# LavaExpress — Home

Sitio estático one-page.

## Abrir

Desde esta carpeta:

```bash
python3 -m http.server 8080
```

Luego: [http://localhost:8080](http://localhost:8080)

## Estructura

```
site/
  index.html
  assets/
    css/           estilos + custom.css
    js/            main.js + contact.js
    img/           imágenes con nombres claros
      brand/ hero/ about/ services/ ...
```

## Qué editar

| Cambio | Archivo |
| --- | --- |
| Textos, menú, secciones | `index.html` |
| Ajustes visuales propios | `assets/css/custom.css` |
| Formularios | `assets/js/contact.js` |
| Fotos | `assets/img/...` |

## Formularios

El formulario de contacto funciona en el navegador y muestra un mensaje de éxito. Todavía no envía a un backend.
