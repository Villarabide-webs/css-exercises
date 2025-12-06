Ejercicio 04 — Encadenar Selectores (Chaining Selectors)

Este ejercicio forma parte de los Fundamentos de CSS y tiene como objetivo practicar cómo seleccionar elementos que tienen dos clases simultáneamente mediante selectores encadenados (por ejemplo: .avatar.proportioned).
El propósito es aplicar estilos diferentes a dos imágenes, aunque compartan una misma clase.

⸻

🎯 Objetivo del ejercicio

Se proporcionó un archivo HTML completo con dos imágenes que comparten la clase avatar pero tienen una segunda clase distinta (proportioned y distorted).
La tarea consiste en:
	•	Aplicar estilos solo cuando ambas clases coinciden en el mismo elemento.
	•	Mantener el estilo separado del resto de imágenes “originales” que aparecen debajo.

⸻

🖼 Estilos requeridos

🔹 Imagen con clases avatar proportioned
	•	Ancho: 300px
	•	Altura: automática (height: auto)
	•	Para que conserve su proporción original (cuadrada)

🔹 Imagen con clases avatar distorted
	•	Ancho: 200px
	•	Altura: 400px
	•	El doble del ancho → debe verse distorsionada

    Explicación técnica
	•	Los selectores encadenados (.avatar.proportioned) permiten apuntar a un mismo elemento que contiene ambas clases.
	•	height: auto obliga al navegador a calcular la altura manteniendo las proporciones originales.
	•	En el segundo caso, se fuerza una deformación al establecer altura fija.