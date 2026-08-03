# NexumCorp — Landing

Landing page de marketing para **NexumCorp**, representante de las marcas **Opel**,
**Peugeot** y **Toyota Industrial** en Ecuador.

## Contenido

- `index.html` — landing principal, con las tres líneas de negocio (autos Opel/Peugeot
  y equipo industrial Toyota).
- `peugeot-landing.html` — landing dedicada a Peugeot ("Motion & Emotion").
- `assets/` — imágenes de vehículos y logos de marca.

## Stack

Sitio 100% estático (HTML/CSS/JS), sin build system. Animaciones con
[GSAP](https://gsap.com/). Los archivos `.htaccess`, `php.ini` y `.user.ini` son
configuración de cPanel autogenerada y no deben editarse a mano.

## Uso

No requiere instalación ni build: basta con servir los archivos estáticos (por ejemplo
con Laragon/Apache) y abrir `index.html`.
