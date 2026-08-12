# Torno y Soldadura Especiales Ángel — Sitio web

Sitio estático de 8 páginas (HTML + CSS + JS vanilla), listo para publicar en GitHub Pages.

## Estructura
```
index.html        Inicio
nosotros.html      Nosotros
servicios.html     Servicios
galeria.html       Proyectos
contacto.html      Contacto
privacidad.html    Política de privacidad
terminos.html      Términos y condiciones
aviso-legal.html   Aviso legal
assets/            CSS, JS, logo, favicon e imágenes propias
robots.txt
sitemap.xml
site.webmanifest
```

## Antes de publicar — pendientes a completar
1. **Dominio real:** en `build.py`, la variable `DOMAIN` está puesta como
   `https://especialesangel.github.io`. Cámbiala por la URL real de tu GitHub
   Pages (o dominio propio) y vuelve a correr `python3 build.py`, o reemplaza
   manualmente ese texto en todos los `.html`, `robots.txt` y `sitemap.xml`.
2. **Enlace de Facebook:** `FB_LINK` está como marcador de posición
   (`https://www.facebook.com/`). Pégale el enlace real de la página.
3. **Horario:** se dejó un texto genérico ("Lunes a sábado — escríbanos para
   confirmar disponibilidad") porque el horario exacto no estaba en los datos
   proporcionados. Edítalo en `contacto.html`.
4. **Dirección exacta:** solo se usó "Managua, Nicaragua" porque no se
   proporcionó una dirección específica. Si quieres un mapa o pin exacto,
   agrégalo en `contacto.html`.

## Publicar en GitHub Pages
1. Crea un repositorio nuevo y sube todo el contenido de esta carpeta a la raíz.
2. En **Settings → Pages**, elige la rama `main` y la carpeta `/root`.
3. Espera unos minutos: tu sitio quedará en `https://<usuario>.github.io/<repo>/`.

## Créditos de imágenes
- Logo: recortado a partir de la imagen provista, con fondo transparente.
- Fotos propias del taller: `assets/rim-real.jpg`, `assets/suelda-real.jpg`.
- Fotos de stock: Pexels (uso comercial gratuito, sin atribución obligatoria).
