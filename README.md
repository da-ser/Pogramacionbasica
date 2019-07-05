# Programacionbasica
# Programación Básica.

----
## Tutorial de Python.

###Operadores
TIPOS DE DATOS BASICOS

En python los tipos de datos básicos se dividen en, números, como pueden ser 3 (entero ó integer) 1.75, (punto flotante ó float) 7+5j (complejos ó complex).

Para poder conocer el tipo de dato de una variable susaremos la instrucción "type()".

Otro tipo de dato basico en PYTHON son las cadenas de texto, por ejemplo, "Hola Mundo" (cadena de texto o string ó 'Hola Mundo' ó "Jenny's dog").

Como se puede notar a diferencia de muchos otros lenguajes en PYTHON no se declara el tipo de variable al crearla.

Para resumir en PYTHON se puede reprecentar números enteros, reales, y complejos. Los números enteros son aquellos números positívos o negatívos que no tienen desimales. En la mayor parte de las maquinas las variables enteras ("int") pueden almacrnar números de -2^31 a 2^31. En plataformas de 64 bites el rango es de -2^63 a 2^63.
Operadores:

		suma                    r=3+2
		resta	                r=4-7
            (guión) negación        r=-7
		multiplicación		r=2*6
		exponente		r=2**6
		división		r=3.5/2
		división entera		r=3.5//2
		modulo (residuo)	r=7%2

Un ejemplo de esto puede ser el siguiente:

    a=int(input('Incerta un numero '))   
    b=int(input('Incerta otro numero '))

    s=a+b   
    print('La suma es ' ,s)    
    r=b-a   
    print('La resta es ' ,r)    
    m=a*b   
    print('El producto es ' ,m)   
    d=a/b   
    print('El residuo es ' ,d)   
    dd=b/a
    print('El resultado es ' ,dd)    
    p=a**b   
    print('El resultado de "a" a la "b" es ' ,p)   
    import math    
    print('El logaritmo es ' ,math.log10(a))
###Ciclo For.
En pyhton "for" se utiliza como una forma genérica de interés sobre una secuencia, es decir, recorrer una secuencia.

            variable = secuencia  
            secuencia = ["uno", "dos", "tres"]  //estos son elementos
            for elemento in secuencia:
                print(elemento)                //4 esopacios 

Y los resultados serán:

           uno
           dos
           tres
    
El siclo "for" debe marcarse con un rango como se muestra de la siguiente manera:

    for temperatura in range(0,100,10):    //range es el rango y va el inicio, hasta
                                             donde quiero llegar y en este caso va de 10
    print(temperatura,'gC')                  en 10.

Un ejemplo del ciclo "for" puede ser el siguiente:

    for celcius in range(0,101,10):
        farenheit = (1.8*celcius)+32
        print(celcius,'gC','|',farenheit,'gF')
###Modulo Turlte 
Hay muchos módulos en python que proveen características poderosas que podemos usar en nuestros propios programas. Algunos de estos pueden enviar correos electrónicos y algunos de estos pueden extraer información de paginas de Internet. Para el manejo de gráficos usaremos un modulo que permite crear figuras y patrones. El modulo que se usara permiten desarrollar nuestro pensamiento computacional.

      
    import turtle
    ventana=turtle.Screen()	//Crea una ventana en blanco			
    alex=turtle.Turtle()	//Crear un objeto de la clase turtle lo puedo llamar como yo quiera se llama "alex" y puede tener atributos
    alex.forward(50)	//Avanza 50 unidades
    alex.left(90)		//gira a la izquierda 90°
    alex.forward(30)	//Avanza 30 unidades
    ventana.mainloop()	//Hasta que el usuario cierra la ventana el programa termina

Un ejemplo del modulo Turtle puede ser:

     import turtle
     ventana=turtle.Screen()
     alex=turtle.Turtle()
     alex.forward(100)
     alex.left(90)
     alex.forward(100)
     alex.left(90)
     alex.forward(100)
     alex.left(90)
     alex.forward(100)
     alex.left(90)
     alex.forward(100)
     ventana.mainloop()

Te aparecera una flecha, y no como tal una tortuga, pero si la quisieras ponlo de la siguiente manera:

    import turtle
    ventana=turtle.Screen()
    ventana.bgcolor('red')
    ventana.title("Hola")

    alex=turtle.Turtle()
    alex.shape("turtle")
    alex.color("blue")
    alex.pensize(10)
    alex.forward(100)
    alex.left(120)
    alex.forward(100)
    ventana.mainloop() 
###Funciónes 

Una función es un fragmento de código con un nombre asociado que realiza una serie de tareas y devuelve un valor. A demás de ayudarnos a programar y depurar dividiendo el programa en partes, las funciones también permiten reutilizar código.
     
	##definicion de una funcion
	def ladra():
	    print('guau, guau')
	##cuerpo principal del programa
	ladra()
Las Funciones ayudan al programador a dividir un problema en pequeñas piezas que pueden ser re usadas. También ayudan al programador a concentrarse en una pequeña parte del programa a la vez. Como resultado el escribir funciones es una parte importante del desarrollo del sofware. 

En nuestro caso debemos aprender a:

	1. Definir una función para usarla después.
	2. Pasar uno o más valores a una función.
	3. Desarrollar un cálculo complejo en una función.
	4. Regresar uno o más resultados a una funci
