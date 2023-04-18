# Simulación de examen Abril 2023

## Ejercicio 1 – Punto - 5 puntos - Para quienes opten a un 5 en el examen
Crea un programa con una clase llamada Punto que representará un punto de dos dimensiones en un plano. Solo contendrá dos atributos enteros llamadas x e y (coordenadas).
En el main de la clase principal instancia 3 objetos Punto con las coordenadas (5,0), (10,10) y (-3, 7). Muestra por pantalla sus coordenadas (utiliza un println para cada punto). Modifica todas las coordenadas (prueba distintos operadores como =  +  -  +=  *=...) y vuelve a imprimirlas por pantalla.

## Ejercicio 1 – Punto -  5 puntos - Para quienes opten hasta a un 10 en el examen
Añade a la clase Punto un constructor con parámetros que copie las coordenadas pasadas como argumento a los atributos del objeto. Así:

    public Punto(int x, int y){    
      this.x = x;
      this.y = y;
    }

Copiamos los valores pasados como argumento a los atirbutos del objeto. Ten en cuenta que int x e int y son variables locales del método, NO son los atributos del objeto. Para hacer referencia a los atributos del objeto hay que utilizar this.
Fíjate que ya no será posible hacer Punto p = new Punto(). Ahora será obligatorio hacer por ejemplo Punto p = new Punto(2, 7). En el apartado A tenías que recordar asignar valores a x e y tras crear un punto, lo cual no es una buena idea en proyectos grandes con cientos de objetos (es muy fácil equivocarse). Ahora es imposible equivocarse porque Java no te dejará. Hemos asegurado que todos los puntos siempre tendrán coordenadas.
Corrige el main y utiliza el constructor con parámetros para instanciar los objetos, pasándole como argumento los valores deseados.
