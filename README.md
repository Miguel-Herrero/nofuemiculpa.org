# No Fue Mi Culpa

Web del proyecto **No Fue Mi Culpa**, contra el abuso sexual en menores y jóvenes en España.

🌐 **Sitio:** https://nofuemiculpa.org

Es una versión estática y ligera de la web original. Está escrita con HTML y CSS puros, sin frameworks ni proceso de compilación.

## Estructura

```
index.html         Inicio
sobre-mi.html      Sobre mí (historia y medios)
recursos.html      Noticias y Datos
el-proyecto.html   El proyecto (vídeo, testimonios, próximamente)
contacta.html      Contacta (email y redes)
privacidad.html    Política de privacidad
404.html           Página de error
styles.css         Estilos de todo el sitio
fonts/             Poppins y Raleway, alojadas en local
img/               Imágenes optimizadas (WebP) y logos
CNAME              Dominio personalizado para GitHub Pages
robots.txt         Reglas para rastreadores
sitemap.xml        Mapa del sitio
```

## Vista previa en local

No hace falta instalar nada más que Python 3:

```bash
python3 -m http.server 8000
```

Después abre http://localhost:8000 en el navegador.

## Publicación

El sitio se publica con **GitHub Pages** desde la rama `main`, carpeta raíz. El fichero `CNAME` apunta al dominio `nofuemiculpa.org`. Conviene activar «Enforce HTTPS» en los ajustes de Pages.

## Notas

- Las fuentes tipográficas se sirven desde el propio dominio, sin peticiones a Google Fonts.
- Los vídeos de YouTube no cargan hasta que el visitante pulsa reproducir.
- Las noticias y los informes enlazan a fuentes externas.
