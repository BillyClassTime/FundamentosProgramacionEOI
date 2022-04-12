# Ejercicios de Algoritmos

1.  Hola Mundo

```
Algoritmo hola_mundo
	Escribir "Hola mundo"
FinAlgoritmo
```

2.  A partir de un número ingresado diga si es mayor, menor o igual a 9.

```
Algoritmo MayoresIgualesMenoresA9
	N<-0
	Escribir "Escribir el numero"
	Leer N
	Si N Es Igual A 9 Entonces
		Escribir "El numero es igual a 9"
	Sino
		Si N Es Mayor Que 9 Entonces
			Escribir "El numero es mayor a 9"
		Sino
			Escribir "El numero es menor a 9"
		Fin Si
	Fin Si
FinAlgoritmo
```

3.  A partir de un número ingresado diga si el mismo es par o impar.

```
Algoritmo ParidadNumeros
	Leer nro
	Si (nro mod 2) = 0 entonces
		Escribir "es par"
	Sino
		Escribir "es impar"
	Fin Si
FinAlgoritmo
```

4.  ingresar dos números y devuelva el resultado de la suma entre ambos.

```
Algoritmo SumaDosNumeros
    Num1<-0
    Num2<-0
    Escribir "Escribir el numero 1"
    	Leer Num1
    Escribir "Escribir el numero 2"
    	Leer Num2
    	Rta<-Num1+Num2
    Escribir "El resultado es:" Rta
FinAlgoritmo
```

5. Sumar todos los números pares entre 2 y 100.

```
Algoritmo SumaDePares
	suma <- 0
	nro <- 2
	Mientras nro<=100 hacer
		si nro mod 2 = 0 Entonces
			suma= suma+nro			
		FinSi
		nro=nro+1
	FinMientras
	Escribir "la suma de los pares entre 2 y 100 es " suma
FinAlgoritmo
```

6. Ingresar un número y muestre todos los divisores del mismo.

```
Algoritmo divisores_de_numero
	Escribir "Ingrese Numero"
	Leer Num
	div<-1
	Mientras Div<=Num Hacer
		Si Num MOD div = 0 
			Escribir div
		Fin Si
		div<-div+1
	Fin Mientras
FinAlgoritmo
```

7. Determinar si un alumno aprueba o suspende un curso, sabiendo que aprobará si su promedio de tres calificaciones es mayor o igual a 4.0; supsende en caso contrario. Deberá permitir ingresar las tres calificaciones y luego calcular su promedio.

```
Algoritmo aprueba_reprueba
	Escribir "Ingrese calificacion 1"
		Leer Cal1
	Escribir "Ingrese calificacion 2"
		Leer Cal2
	Escribir "Ingrese calificacion 3"
		Leer Cal3
	Prom<-(Cal1+Cal2+Cal3)/3 	                           
        Si Prom>=4 Entonces
		Escribir "Aprueba"
	Sino
		Escribir "Reprueba"
	Fin Si
	Escribir Prom
FinAlgoritmo
```

8. Crear un algoritmo que permita ingresar un nombre y una cantidad numérica para escribir este nombre tantas veces como su cantidad ingresada. 

```
Algoritmo Cantidad_nombre
	Escribir "Ingresar Nombre"
	Leer nombre
	Escribir "Ingresar Cantidad"
	Leer num
	Mientras Num>0 Hacer
		Escribir nombre
	Num<-Num - 1
	Fin Mientras
FinAlgoritmo
```

9. Sumar todos los números naturales comprendidos entre 1 y 50.

```
Algoritmo suma_numerosnaturales_1y50 
	Num<-1
	Resul<-0
	Repetir
	    Resul<-Resul+Num
	    Num<-Num+1 	                           
        Hasta Que Num>50
	Escribir Resul
Fin algoritmo
```

10. Leer tres números; si el primero es negativo, debe imprimir la multiplicación de los tres y si no lo es, imprimirá la suma.

```
Algoritmo tresnumeros
	Escribir "Ingrese numero 1"
		Leer Num1
	Escribir "Ingrese numero 2"
		Leer Num2
	Escribir "Ingrese numero 3"
		Leer Num3
	Si Num1<0 Entonces
		Resul<-Num1 * Num2 * Num3
	Sino
		Resul<-Num1+Num2+Num3
	Fin Si
	Escribir Resul
FinAlgoritmo
```

11. Si un número ingresado es primo o no. (Un número es primo si es divisible únicamente por 1 y por sí mismo).

```
Algoritmo NumerosPrimos
	Escribir "Ingrese un número: "
	Leer nro
	div <- 2
	band <- Verdadero 	         
        Si nro=1 Entonces 		            
             Escribir "Es primo" 	         
        Sino 		             
             Mientras band=Verdadero y nro>div Hacer
		Si nro MOD div = 0 Entonces
		    band <- Falso
		FinSi
		    div <- div +1
	     FinMientras
	     si band= Verdadero Entonces
		Escribir "Es primo"
	     Sino
		Escribir "No es primo"
	     FinSi
	FinSi
FinAlgoritmo
```

12 . Sumar los dígitos de un número ingresado. Ejemplo: Si se ingresa 123, debería devolver 6.

```
Algoritmo SumaDigitos
	Escribir "Ingrese un nro: "
	Leer nro
	resul <- 0
	Mientras nro <> 0 Hacer
		resul <- resul + nro MOD 10
		nro <- trunc(nro/10)
	FinMientras
	Escribir "El resultado es: " resul
FinAlgoritmo
```

13. Ejercicios Propuestos
    1. Calcular y mostrar el cuadrado de los números del 1 a 30.
    2. Números primos
    3. Construir un avión de papel
    4. Realizar las cuatro operaciones básicas (Suma, Resta, Multiplicación, División)
    5. Volumen y Area de un Cilindro
    6. Pedir un libro en una biblioteca
    7. Encontrar el mayor número de tres números
    8. Factorial de cualquier número
    9. Encontrar si un numero en mayor o menor a un número dado.
    10. Adivinar una palabra.