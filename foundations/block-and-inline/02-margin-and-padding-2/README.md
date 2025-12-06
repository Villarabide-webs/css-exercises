Ejercicio 02 — Margin and Padding #2

Curso: Foundations – Block and Inline

Este ejercicio consiste en practicar el uso de márgenes (margin) y rellenos internos (padding), así como algunos ajustes básicos de estilo, para recrear una tarjeta (card) visualmente similar a la imagen de referencia.

El HTML ya está proporcionado, por lo que solo debías modificar el archivo style.css, respetando la estructura original de clases:
.card, .title, .content, .button-container, button.

⸻

🎯 Objetivo del ejercicio

Reproducir la tarjeta del desired outcome, ajustando:
	•	Margins → Espacio entre elementos y separación exterior.
	•	Padding → Espacio interior dentro de cada caja.
	•	Alineación del texto y los botones.
	•	Tamaño y estilo del botón.
	•	Separación entre bloques internos.
	•	Tamaño de fuente razonable (no hace falta perfección pixel-perfect).
	•	No modificar el HTML, solo editar el CSS.

⸻

🧠 Conceptos importantes repasados

🟦 margin

Define el espacio exterior de un elemento.
Ejemplo: separar .card del resto de la página.

🟩 padding

Define el espacio interno dentro de cada caja.
Ejemplo: que el texto dentro de .content no pegue al borde.

🟥 Bloques (display: block)

Elementos como <div> y <h1> ocupan todo el ancho disponible por defecto.
Por eso deben estilizarse con márgenes y padding para formar la tarjeta.

🟧 Flexbox

Usado para colocar el texto and a y el botón uno encima del otro:
display: flex;
flex-direction: column;
align-items: center;