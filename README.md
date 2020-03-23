# Funcion suma  
def suma(num1, num2): 
    return num1 + num2 
  
# Funcion resta 
def resta(num1, num2): 
    return num1 - num2 
  
# Funcion multiplicacion 
def multiplicacion(num1, num2): 
    return num1 * num2 
  
# Funcion division 
def division(num1, num2): 
    return num1 / num2 

# Fucnion modulo
def modulo(num1, num2):
  return num1 % num2

#Operaciones trigonometricas
from math import cos, sin,tan,acos,asin,atan,degrees,radians
def coseno(num1):
    return cos(radians(num1)) 

def seno(num1):
    return sin(radians(num1))

def tangente(num1):
    return tan(radians(num1))

def acoseno(num1):
    return cos(degrees(num1)) 

def aseno(num1):
    return sin(degrees(num1))

def atangente(num1):
    return tan(degrees(num1))

  
print("Seleccione opcion -\n" 
        "1. Suma\n" 
        "2. Resta\n" 
        "3. Multiplicacion\n" 
        "4. Division\n"
        "5. Modulo\n"
        "6. Operaciones Trigonometricas \n") 
  
  
opcion = input("Seleccione operaciones de 1, 2, 3, 4, 5, 6 :") 
  
numero_1 = int(input("Ingrese primer numero: ")) 
numero_2 = int(input("Ingrese segundo numero: ")) 
  
if opcion == '1': 
    print(numero_1, "+", numero_2, "=", 
                    suma(numero_1, numero_2)) 
  
elif opcion == '2': 
    print(numero_1, "-", numero_2, "=", 
                    resta(numero_1, numero_2)) 
  
elif opcion == '3': 
    print(numero_1, "*", numero_2, "=", 
                    multiplicacion(numero_1, numero_2)) 
  
elif opcion == '4': 
    print(numero_1, "/", numero_2, "=", 
                    division(numero_1, numero_2)) 
elif opcion == '5':
    print(numero_1, "%", numero_2,"=", modulo(numero_1,numero_2))

if opcion=='6':
   print("¿Que funcion desean utilizar? \n"
        " 1. Seno (Radianes) \n"
        " 2. Coseno (Radianes) \n"
        " 3. Tangente (Radianes) \n"
        " 4. Aseno (Grados) \n"
        " 5. Acoseno (Grados) \n"
        " 6. Atangente (Grados) \n")

res = int(input("Seleccione opcion: 1, 2, 3, 4, 5, 6: "))
x= float(input("Ingrese numero: "))

if res == '1':
    x= float(input("Ingrese numero: "))
    print("El resultado es = ", sin(x))
    
elif res == '2':
    x= float(input("Ingrese numero: "))
    print("El resultado es = ", cos(x))
    
elif res == '3':
    x= float(input("Ingrese numero: "))
    print("El resultado es = ", tan(x))
    
elif res == '4':
    x= float(input("Ingrese numero: "))
    print("El resultado es = ", aseno(x))
    
elif res == '5':
    x= float(input("Ingrese numero: "))
    print("El resultado es = ", acoseno(x))

elif res == '6':
    x= float(input("Ingrese numero: "))
    print("El resultado es = ", atangente(x))

else: 
    print("Opcion invalida") 
