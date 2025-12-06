Objetivo del ejercicio

Aplicar estilos a dos elementos usando:
	•	✔ Clases únicas para cada elemento
	•	✔ Selector agrupado para estilos comunes
	•	✔ Selectores individuales para estilos exclusivos

Los estilos requeridos eran:

🔹 Estilos comunes (para ambos elementos)
	•	Tamaño de fuente: 28px
	•	Lista de fuentes: Helvetica, Times New Roman, sans-serif

🔹 Estilos únicos
	•	Primer elemento (.caja1)
	•	Fondo negro
	•	Texto blanco
	•	Segundo elemento (.caja2)
	•	Fondo amarillo
	•	Texto negro

⸻

🧩 Estructura del ejercicio

HTML

Se añadieron dos botones, cada uno con su clase:
<button class="caja1">Click Me!</button>
<button class="caja2">No, Click Me!</button>
CSS

Se utilizó un selector agrupado para los estilos comunes y reglas individuales para los estilos específicos:
.caja1,
.caja2 {
  font-size: 28px;
  font-family: "Helvetica", "Times New Roman", sans-serif;
}

.caja1 {
  background-color: black;
  color: white;
}

.caja2 {
  background-color: yellow;
  color: black;
}