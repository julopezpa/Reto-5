# Reto-5
estaba extraño 
# 1
Dado un número entero, determinar si ese número corresponde al código ASCII de una vocal minúscula.

![image](https://user-images.githubusercontent.com/124606636/222995461-7c3bff73-569d-4911-9166-4cc740f5b0d2.png)

    #Programa para identificar si corresponde a una vocal minuscula
    n=int(input("ingrese un numero "))
    if n==97:
      print("el numero "+str(n)+" corresponde a la vocal "+ chr(n)+" minuscula")
    elif n==101:
      print("el numero "+str(n)+" corresponde a la vocal "+ chr(n)+" minuscula")
    elif n==105:
      print("el numero "+str(n)+" corresponde a la vocal "+ chr(n)+" minuscula")
    elif n==111:
      print("el numero "+str(n)+" corresponde a la vocal "+ chr(n)+" minuscula")
    elif n==117:
      print("el numero "+str(n)+" corresponde a la vocal "+ chr(n)+" minuscula")
    else:
      print("el numero "+str(n)+" no corresponde a ninguna vocal minuscula, ya que es el caracter "+ chr(n))
# 2
Dada una cadena de longitud 1, determine si el código ASCII de primera letra de la cadena es par o no.

![image](https://user-images.githubusercontent.com/124606636/222995588-fc0fd4c8-5ac9-4963-8eb2-51ccf67b18e0.png)

    #Programa para identificar si una cadena de caracter de longitud 1, es par o impar (ASCII)
    n=input("ingrese un caracter de longitud 1")
    ord(n)
    x=ord(n)
    if x%2 == 0:
      print("el caracter "+str(n)+" es par")
    else :
      print("el caracter "+str(n)+" es impar")
# 3
Dado un carácter, construya un programa en Python para determinar si el carácter es un d´ıgito o no.

![image](https://user-images.githubusercontent.com/124606636/222995693-ffdd6549-6ea8-4b16-bf69-65e0e45e27bf.png)

    #Programa para identifucar si el caracter es un digito
    n=input("ingrese un solo caracter")
    ord(n)
    x=ord(n)
    if x>57:
        print("el caracter "+str(n)+" no es un digito/numero")
    elif x<48:
        print("el caracter "+str(n)+" no es un digito/numero")
    else :
        print("el caracter "+str(n)+" es un digito/numero")
# 4
Dado un número real x, construya una función que permita determinar si el número es positivo, negativo o cero.

![image](https://user-images.githubusercontent.com/124606636/222995767-a6671b64-ca2f-4592-b760-dd351bbb71f9.png)

    #Programa para ver si un numero real es positivo, negativo o neutro
    x=float(input("ingrese un numero real"))
    if x>0:
        print("El número x es positivo")
    elif x<0:
        print("El número x es negativo")
    else:
        print("El número x es el neutro para la suma")
# 5
Dado el centro y el radio de un c´ırculo, determinar si un punto de R2 pertenece o no al interior del c´ırculo.

![image](https://user-images.githubusercontent.com/124606636/222995903-3ee35d70-c789-4dd3-9ddd-ca40cc649451.png)

    #Programa para determinar si un punto pertenece o no al interior de un circulo 
    x=float(input("ingrese coordenadas para x"))
    y=float(input("ingrese coordenadas para y"))
    c=float(input("ingrese longitud del radio"))
    x1=float(input("ingrese la primera coordenada del centro"))
    y1=float(input("ingrese la segunda coordenada del centro"))
    if ((x-x1)**2)+((y-y1)**2)<=c**2:
        print("el punto pertenece al interior del circulo")
    else:
        print("el punto no pertenece al interio del circulo")
#6
Dadas tres longitudes positivas, determinar si con esas longitudes se puede construir un triángulo.

![image](https://user-images.githubusercontent.com/124606636/222995964-3009d565-a70f-48bf-9e36-29cfdb9fe757.png)

    #Programa para decir si es posible o no crear un triangulo con medidas x
    a=float(input("ingrese la primera longitud positiva"))
    b=float(input("ingrese la segunda longitud positiva"))
    c=float(input("ingrese la tercera longitud positiva"))
    if a<=0 or b<=0 or c<=0:
        print("no son longitudes positivas")
    elif a + b > c and a + c > b and b + c > a:
        print("se puede construir un triangulo")
    else:
        print("con esas longitudes no se puede construir un triangulo ")
        
# meme random 

![image](https://user-images.githubusercontent.com/124606636/222996189-41d36a88-b77e-4ded-930f-66846c69ea41.png)
