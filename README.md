# Concurso de Preguntas

Juego de preguntas tipo concurso de televisión para clase: el profesor carga un JSON con sus preguntas y se juega en el proyector, con escalera de premios, comodines (50:50, público, llamada), sonidos y animaciones.

**Jugar:** https://miguelmatmar.github.io/millonario/

## Modos
- **Toda la clase:** escalera de premios clásica, con seguros y opción de plantarse.
- **Dos equipos (rojo vs azul):** turnos alternos, marcador, comodines por equipo y rebote (si un equipo falla, el otro puede responder por la mitad de puntos).

## Cómo crear tus preguntas
1. Descarga [`plantilla.json`](plantilla.json) (o pulsa «Descargar plantilla» en la web).
2. Cambia las preguntas. Cada una necesita `pregunta`, 4 `opciones` y `correcta` (`"A"`, `"B"`, `"C"` o `"D"`). `explicacion` e `imagen` son opcionales.
3. Súbelo o pégalo en la página y pulsa «Comprobar y continuar».

También puedes pulsar «Copiar instrucciones para una IA», pegarlas en un chat de IA con tu tema, y pegar el JSON que te devuelva. Revisa siempre las respuestas.

## Controles
`A`–`D` elegir · `Enter` confirmar · `M` silenciar · `F` pantalla completa

Todo funciona en un único `index.html`, sin servidor ni instalación.
