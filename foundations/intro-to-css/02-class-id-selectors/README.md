Ejercicio 02: Selectores de Clases e IDs

🎯 Descripción del ejercicio

En este ejercicio se pedía practicar el uso de los selectores class e id en HTML y CSS, identificando correctamente cuándo usar cada uno.

El objetivo principal era:
	•	Agrupar elementos con estilos similares mediante clases
	•	Asignar estilos exclusivos a elementos únicos usando IDs
	•	Aplicar varias clases a un mismo elemento cuando necesitaba estilos combinados
	•	Utilizar colores en formatos RGB, HEX o HSL, evitando palabras clave

⸻

🛠️ Solución aplicada

✔ 1. Clase .odd para los elementos impares

Se creó la clase odd para los elementos 1, 3 y 5, ya que compartían los mismos estilos:
	•	Fondo rosa claro
	•	Fuentes: "Verdana", "DejaVu Sans", sans-serif

Se añadió así:
<p class="odd">...</p>
Y en CSS:
.odd {
  background-color: #ffd6dc;
  font-family: "Verdana", "DejaVu Sans", sans-serif;
}
 2. ID #second para el elemento 2 (estilo único)

El segundo elemento tiene un estilo exclusivo, así que se usó un ID:
	•	Texto azul (RGB)
	•	Tamaño 36px
    <div id="second">...</div>
    #second {
  color: rgb(0, 102, 204);
  font-size: 36px;
}
3. Clase extra .large para el elemento 3

El elemento 3 debía tener los estilos de los impares más un tamaño de letra mayor (24px).
Por eso se aplicaron dos clases:
<p class="odd large">...</p>

css
.large {
  font-size: 24px;
}

4. ID #fourth para el elemento 4 (otro estilo único)
	•	Fondo verde claro (HSL)
	•	Tamaño 24px
	•	Negrita 
    html
    <div id="fourth">...</div>

css 
#fourth {
  background-color: hsl(120, 60%, 90%);
  font-size: 24px;
  font-weight: bold;
}









Class para varios elementos con el mismo estilo
id para un unico elemento solo puedo aver un id="x" por pagina