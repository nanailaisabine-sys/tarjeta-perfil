# Pioneros de la computación

Tarjetas de perfil de Ada Lovelace, Alan Turing y Grace Hopper, con efectos al pasar el mouse que también funcionan con el teclado. Es el proyecto 8 de mi ruta de 100 proyectos de desarrollo web.

![Tarjetas de perfil con la tarjeta central elevada](img/captura.png)

## Tecnologías
- HTML5 semántico
- CSS (Flexbox, transform y transition)

## Lo que aprendí
- Acomodar tarjetas que se reorganizan solas con `flex: 1 1 280px` y `flex-wrap`, sin consultas de medios
- Mover y escalar elementos con `transform` sin afectar al resto de la página
- Animar cambios con `transition`, y por qué va en el estado normal y no en `:hover`
- Recortar una imagen dentro de su marco con `overflow: hidden`
- Hacer que toda una tarjeta reaccione con `.bloque:hover .elemento`
- Que los efectos también respondan al teclado con `:focus-within` y `:focus-visible`
- Dar sensación de clic con `:active`
- Respetar a quien pide menos movimiento con `prefers-reduced-motion`

## Accesibilidad
- Todos los efectos funcionan con el teclado, no solo con el mouse.
- Si el sistema operativo tiene activada la reducción de movimiento, las tarjetas no se desplazan, pero siguen destacándose con su sombra.

## Créditos
- Retratos de dominio público, vía Wikimedia Commons.

## Cómo verlo
Descarga el repositorio y abre `index.html` en tu navegador.