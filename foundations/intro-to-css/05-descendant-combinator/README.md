Ejercicio 05 — Combinador Descendiente (Descendant Combinator)

Este ejercicio forma parte de los Fundamentos de CSS y tiene como objetivo entender cómo funcionan los combinadores descendientes, una herramienta clave para aplicar estilos solo a elementos que están dentro de otros elementos.

El HTML proporcionado ya está completamente preparado, por lo que no es necesario modificarlo. Tu trabajo consiste únicamente en escribir reglas CSS que afecten solo a ciertos elementos, según su relación en el árbol DOM.

⸻

🎯 Objetivo del ejercicio

Aplicar estilos únicamente a los elementos <p> que son descendientes de un <div>, sin afectar a los <p> que no estén dentro de un <div>.

⸻

🧩 Estilos requeridos

Los <p> dentro del <div> deben tener:
	•	Fondo: amarillo
	•	Texto: rojo
	•	Tamaño de fuente: 20px
	•	Alineación: centrada

Los <p> que NO son descendientes del <div>:
	•	❌ No deben recibir ningún estilo

⸻

🧠 Solución implementada (CSS)
div p {
  background-color: yellow;
  color: red;
  font-size: 20px;
  text-align: center;
}
Explicación técnica

El selector:
div p
es un combinador descendiente, lo que significa:

“Selecciona todos los <p> que estén dentro de un <div>, sin importar el nivel de profundidad.”

De esta forma:
	•	Los <p> dentro del <div> reciben los estilos.
	•	Los <p> fuera del <div> se mantienen completamente sin cambios.
