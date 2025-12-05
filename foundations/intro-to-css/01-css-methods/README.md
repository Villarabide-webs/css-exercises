Ejercicio 01: Métodos para Añadir CSS

🎯 Descripción del ejercicio

En este ejercicio se pedía practicar las tres formas de añadir CSS a un documento HTML:
	1.	CSS externo
	2.	CSS interno
	3.	CSS inline

Además, el ejercicio indicaba:
	•	Usar solo selectores de tipo (por ejemplo, div, p, button)
	•	Usar colores por palabra clave (como “red”, “green”, “orange”)
	•	Crear manualmente un archivo externo llamado style.css y enlazarlo al HTML
	•	Aplicar un método distinto de CSS a cada elemento (div, p, button)

⸻

🛠️ Solución aplicada

✔ 1. CSS externo — aplicado al <div>
	•	Creé el archivo style.css
	•	Lo enlacé en el <head> con <link rel="stylesheet">
	•	Añadí estilos al div usando un selector de tipo

Estilos aplicados:
	•	Fondo rojo
	•	Texto blanco
	•	Tamaño 32px
	•	Negrita
	•	Texto centrado

⸻

✔ 2. CSS interno — aplicado al <p>

Dentro del <head> agregué un bloque:
<style> … </style>
Y dentro definí los estilos del elemento <p>.

Estilos aplicados:
	•	Fondo verde
	•	Texto blanco
	•	Tamaño 18px

⸻

✔ 3. CSS inline — aplicado al <button>

Directamente dentro de la etiqueta del botón añadí:
style="background-color: orange; font-size: 18px;"
Estilos aplicados:
	•	Fondo naranja
	•	Tamaño 18px
