# core-code-from-scratch-readme
<h1> Week 1 - Algorithms </h1>
<h1> Week Challenges <br> (Wednesday) </h1>
<h2> 1. Let's make pizza 🍕 </h2>
<b> Description </b><br>
Design an algorithm to prepare a pizza from scratch. Define the ingredients, what will be the flavor and the preparation.
<h3> Solution: </h3>
<b> Flavor: Pepperoni pizza. <br></br>
Ingredients:
<ul>
  <li> Pizza dough. </li>
  <li> Pizza sauce: </li>
  <ul>
    <li> Tomato sauce. </li>
    <li> Kosher salt. </li>
    <li> Ground black pepper. </li>
    <li> Granulated garlic. </li>
    <li> Granulated onion. </li>
    <li> Red bell pepper flakes. </li>
    <li> Olive oil. </li>
  </ul>
  <li> Pepperoni. </li>
  <li> Shredded mozzarella cheese. </li>
  <li> Fresh oregano (optional). </li>
  <li> Flour. </li>
</ul><br>
<b> Preparation: </b>
<ol>
  <li> Procurement of ingredients. </li>
  <li> Preheat the oven. </li>
  <li> Prepare the sauce. </li>
  <li> Roll out the dough. </li>
  <li> Add the ingredients. </li>
  <li> Cooking pizza. </li>
  <li> Cut and serve (optional: add oregano). </li>
</ol>

# <h2> 2. Hot N Cold 🤒 🧊 🔥 </h2>
<b> Description </b><br>
Define an algorithm that is able to convert temperatures from Celsius to Fahrenheit and vice versa.
<h3> Solution: </h3>
<ol>
  <li> Obtain the temperature value to be converted. </li>
  <li> If the temperature value is in degrees Fahrenheit, then use Formula A. </li>
  <li> Else (if in degrees Celcius) use Formula B. </li>
</ol><br>
<b> A. Formula to convert from degrees Fahrenheit to degrees Celsius: </b>
<ol>
  <li> I calculate C=(F-32)*5/9 where F is the temperature in degrees Fahrenheit. </li>
  <li> The final result C is the temperature in degrees Celcius. </li>
</ol><br>
<b> B. Formula to convert from degrees Celsius to degrees Fahrenheit: </b>
<ol>
  <li> I calculate F=(C*9/5)+32 where C is the temperature in degrees Celcius. </li>
  <li> The final result F is the temperature in degrees Fahrenheit. </li>
</ol>

# <h2> 3. Some geometry 📐 </h2>
<b> Description </b>
Design an algorithm to calculate the volume of a pyramid, a cube and a sphere.
<h3> Solution: </h3>
<ol>
  <li> Knowing the body for which to calculate the volume </li>
  <li> If the body is a pyramid, then use Formula A. </li>
  <li> Else (if it is a cube) use Formula B. </li>
  <li> Else (if it is a sphere) use Formula C. </li>
</ol><br>
<b> A. Formula to calculate the volume of a pyramid: </b>
<ol>
  <li> I calculate V=1/3*b*a*h where b is the length of the base, a is the width of the base, and h is the height of the pyramid. </li>
  <li> The final result V is the volume of the pyramid. </li>
</ol><br>
<b> B. Formula to calculate the volume of a cube: </b>
<ol>
  <li> I calculate V=l^3 where l is the length of an edge of the base of the cube. </li>
  <li> The final result V is the volume of the cube. </li>
</ol><br>
<b> C. Formula to calculate the volume of a sphere: </b>
<ol>
  <li> I calculate V=4/3*π*r^3 where r is the radius of the sphere and π is the number pi.
  <li> The final result V is the volume of the sphere. </li>
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

  
  
  
    
    
    




    




  
  
  
    
    
    

