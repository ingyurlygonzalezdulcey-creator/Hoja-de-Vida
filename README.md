# Hoja de vida web · Yurly Zyrley Gonzalez Dulcey

Sitio personal con mi hoja de vida, mi hobby AE Floristería y mi sueño cumplido París. Desarrollado con HTML y CSS responsive Mobile First.

🔗 **Sitio publicado:** https://TU-USUARIO.github.io/hoja-de-vida/

## Páginas
- index.html: hoja de vida (perfil, formación, experiencia, habilidades)
- hobby.html: Mi hobby - AE Floristería y Eventos
- paris.html: Mi sueño cumplido - París

## Mockups
### Hoja de vida - index.html
![Inicio en celular](mockups/inicio-celular.png)
![Inicio en computador](mockups/inicio-computador.png)

### Hobby
![Hobby en celular](mockups/hobby-celular.png)
![Hobby en computador](mockups/hobby-computador.png)

### París
![París en celular](mockups/paris-celular.png)
![París en computador](mockups/paris-computador.png)

## Capturas del sitio publicado
R17 - Capturas en 2 dispositivos, una de dispositivo real

![Celular](capturas/celular.png)
![Computador](capturas/computador.png)

> Nota: Al menos una captura es de un celular real abriendo el link publicado.

## Breakpoints
R18 - Explicación corta de mis breakpoints

- **Base (celular):** Todo en una columna. grid-template-areas: cabecera, menu, principal, pie. Es Mobile First.
- **Desde 600px:** Las tarjetas de habilidades pasan de 1 a 2 columnas con repeat(auto-fit, minmax(160px, 1fr)). El contenido crece.
- **Desde 1024px:** El layout cambia: el menú pasa a la izquierda y el contenido principal a la derecha. Es donde se nota el cambio de grid-template-areas.

## Cómo lo publiqué
R19 - Pasos en mis palabras

1. Creé cuenta en GitHub y un repositorio público llamado hoja-de-vida.
2. Subí mis archivos: index.html, hobby.html, paris.html, styles.css y carpetas img/, mockups/, capturas/ (todo en minúsculas).
3. En el repositorio entré a Settings > Pages, en Branch elegí main y carpeta / (root).
4. Esperé 2-3 minutos y GitHub me generó el link https://TU-USUARIO.github.io/hoja-de-vida/
5. Verifiqué que el link abriera en incógnito y en mi celular, y que las imágenes de img/foto.jpg cargaran (error de mayúsculas).

## Fuentes consultadas
- docs.github.com - GitHub Pages - Cómo activar Pages
- MDN Web Docs - CSS Grid y grid-template-areas
- MDN Web Docs - repeat() y minmax()
- W3C Validator - validator.w3.org para validar HTML
- Figma - para hacer los mockups