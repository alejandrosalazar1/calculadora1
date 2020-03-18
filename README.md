  
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
  
print("Seleccione opcion -\n" 
        "1. Suma\n" 
        "2. Resta\n" 
        "3. Multiplicacion\n" 
        "4. Division\n"
        "5. Modulo\n") 
  
  
opcion = input("Seleccione operaciones de 1, 2, 3, 4, 5 :") 
  
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
else: 
    print("Opcion invalida") 
