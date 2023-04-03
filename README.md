# core-code-from-scratch-readme

<h1> Week 1 - Algorithms </h1>

<h1> Week Challenges <br> (Wednesday) </h1>
<h2> 1. Let's make pizza 🍕 </h2>
<b> Design an algorithm to prepare a pizza from scratch. Define the ingredients, what will be the flavor and the preparation. </b>

<h3> Solution </h3>
<b> Sabor: Pizza de mozzarella y tomate <br></br>
Ingredientes:
<ul>
  <li> Masa de pizza </li>
  <li> Salsa de pizza </li>
  <ul>
    <li> Salsa de tomate </li>
    <li> Sal kosher </li>
    <li> Pimienta negra molida </li>
    <li> Ajo granulado </li>
    <li> Cebolla granulada </li>
    <li> Hojuelas de pimiento rojo </li>
    <li> Aceite de oliva </li>
  </ul>
  <li> Pepperoni </li>
  <li> Queso mozzarella rayado </li>
  <li> Oregano fresco (opcional) </li>
  <li> Harina </li>
</ul><br>
<b> Preparación: </b>
<ol>
  <li> Conseguir los ingredientes </li>
  <li> Precalentar el horno </li>
  <li> Preparar la salsa </li>
  <li> Estirar la masa </li>
  <li> Agregar los ingredientes </li>
  <li> Cocinar la pizza </li>
  <li> Cortar y servir (opcional: agregar oregano) </li>
</ol><br>

<h2> 2. Hot N Cold 🤒 🧊 🔥 </h2>
<b> Define an algorithm that is able to convert temperatures from Celsius to Fahrenheit and vice versa. </b>

<h3> Solution </h3>

<ol>
  <li> Definir el valor de temperatura a convertir </li>
  <li> Si el valor de temperatura está en Fahrenheit entonces ultilizar Fórmula A. </li>
  <li> Sino (Si está en Celcius) utilizar Fórmula B. </li>
</ol><br>

<b> A. Fórmula para convertir Fahrenheit a Celsius: </b>
<ol>
  <li> Defino la fórmula C=(F-32)*5/9 siendo F la temperatura en fahrenheit.
  <li> El resultado final C es la temperatura en Celcius. </li>
</ol><br>

<b> B. Fórmula para convertir de Celsius a Fahrenheit: </b>
<ol>
  <li> Defino la fórmula F=(C*9/5)+32 siendo C la temperatura en celcius.
  <li> El resultado final F es la temperatura en Fahrenheit. </li>
</ol>

# <h2> 3. Some geometry 📐 </h2>
<h3> Description </h3>
<b> Design an algorithm to calculate the volume of a pyramid, a cube and a sphere. </b>
<h3> Solution </h3>
<ol>
  <li> Definir el cuerpo a calcular el volumen </li>
  <li> Si el cuerpo es una piramide entonces ultilizar Fórmula A. </li>
  <li> Sino (Si es un cubo) utilizar Fórmula B. </li>
  <li> Sino (Si es una esfera) utilizar Fórmula c. </li>
</ol><br>

<b> A. Fórmula para calcular el volumen de una piramide: </b>
<ol>
  <li> Defino la fórmula V=1/b*l*a*h siendo b el largo de la base, a el ancho de la base, y h la altura de la piramide. </li>
  <li> El resultado final V es el volumen de la piramide. </li>
</ol><br>

<b> B. Fórmula para calcular el volumen de un cubo: </b>
<ol>
  <li> Defino la fórmula V=l^3 siendo l la longitud de una arista de la base del cubo. </li>
  <li> El resultado final V es el volumen del cubo
</ol><br>

<b> C Fórmula para calcular el volumen de una esfera: </b>
<ol>
  <li> Defino la fórmula V=4/3*π*r^3 siendo r el radio de la esfera.
  <li> El resultado final V es el volumen de la esfera.
</ol>

# <h1> Week Challenges <br> (Thursday) </h1>
<h2> 4. Numbers 📈 </h2>
<h3> Description </h3>
<b> Design an algorithm to check if a number is even or odd. If it is even, write that it is even, otherwise write that it is odd. Represent the algorithm in a flowchart. </b>

<h3> Solution </h3>

![Week 1 - Exercice 4](https://user-images.githubusercontent.com/87130341/229401391-6ed03a96-8c40-4f84-ba6b-b3df3f1973b2.png)

# <h2> 5. How old are you 👴 </h2>
<h3> Description </h3>
<b> Write pseudocode for an algorithm that calculates the age of a person based on date of birth </b>
<h3> Solution </h3>

<ol>
  <li> BEGIN <br> OUTPUT("What's your date of birth?"); </li>
  <li> INPUT(date of birth);</li>
  <li> SAVE date of birth -> date_of_birth; </li>
  <li> DEFINE current year -> rigth_now; </li>
  <li> DEFINE age -> age; </li>
  <li> RESULT age=rigth_now-date_of_birth; </li>
  <li> OUTPUT("is" + age + "years old"); </li>
  <li> END. </li>
</ol>

# <h2> 6. Find the treasure 👑 </h2>
<h3> Description </h3>
<b> We are in a room with three chests. We know that at least one has a treasure in it. Each chest has a message, but all the messages are lies. </b><br></br>
Left chest: The middle chest has a treasure <br>
Middle chest: All these chests have treasures in them <br>
Right chest: Only one of these chests has treasures. <br></br>
Which chests have treasures? <br></br>
<img width="354" alt="202836372-19159ef8-14d5-4ecf-b08c-819b05e79f81" src="https://user-images.githubusercontent.com/87130341/229407959-f4e870f9-ee3f-4cc2-b490-e0812bcb240b.png">
<h3> Solution </h3>
<ol>
  <li> Como todos los mensajes son mentira, cambiemos a verdad: <br>
  Left chest: The middle chest has no treasure <br>
  Middle chest: No all chests have treasures on them <br>
  Right chest: It's not possible for Only one of the chests to have a treasure. <br></br> </li>
  <li> Tenemos dos opciones:
  <ul> Ninguno de los cofres tiene un tesoro </ul>
  <ul> Los cofres de la izquierda y derecha tienen un tesoro </ul>
  </li>
  <li> Sabemos que al menos un cofre tiene un tesoro, entonces la única opción es que los cofres de la izquierda y derecha tienen un tesoro. </li>
  <li> Respuesta: Los cofres A y C tienen tesoros. </li>
</ol>

  
  
  
    
    
    




    




  
  
  
    
    
    

