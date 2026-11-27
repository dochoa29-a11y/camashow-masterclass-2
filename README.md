# CAMASHOW MASTERCLASS 2.0 · Itinerario

Página web del itinerario de las dos jornadas de CAMASHOW MASTERCLASS 2.0.
Es un sitio estático (HTML, CSS y JavaScript en un solo archivo): no necesita instalar nada ni compilar.

## Estructura

```
index.html                      Página completa (estilos y scripts incluidos)
assets/                         Logo, rótulos «Itinerario día 1/2» y foto de Camashow
Imagenes de referencia/         Fondos holográficos de la portada y del cierre
netlify.toml                    Configuración de despliegue
```

## Ver la página en tu computador

Abre `index.html` con doble clic. No necesita servidor.

## Publicar en Netlify

1. Entra a [app.netlify.com](https://app.netlify.com) e inicia sesión con tu cuenta de GitHub.
2. Pulsa **Add new site → Import an existing project → GitHub**.
3. Elige este repositorio.
4. Deja la configuración tal como aparece (Netlify la lee de `netlify.toml`):
   - Build command: *vacío*
   - Publish directory: `.`
5. Pulsa **Deploy**. En uno o dos minutos tendrás la URL pública.

Cada vez que subas un cambio a la rama `main`, Netlify vuelve a publicar la página automáticamente.
