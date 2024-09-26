# examen_primer_parcial-3-w
examen del primer parcial 

# Función para encontrar el mayor y menor de tres valores distintos
def encontrar_mayor_menor(A, B, C): #deninifr cual es mayor 
    mayor = A #valor A mayor
    menor = A #valor A menor 

    if B > mayor: #valor B mayor
        mayor = B #identifica el valor mayor 
    if C > mayor: #valor C mayor 
        mayor = C #identificar el valor mayor 

    if B < menor: #valor b menor 
        menor = B #identificar el valor menor 
    if C < menor: #valor C menor 
        menor = C#identificar el valor menor 

    return mayor, menor #para finalizar el programa 

# Leer los valores
A = float(input("Introduce el primer valor (A): ")) #pide al usuario ingresar un valor 
B = float(input("Introduce el segundo valor (B): "))#pide al usuario ingresar un valor
C = float(input("Introduce el tercer valor (C): "))#pide al usuario ingresar un valor

# Comprobar si los valores son distintos
if A == B or A == C or B == C: #el reultado del valor 
    print("Alerta: Los valores introducidos deben ser distintos.")
else: #para finalizar el programa 
    mayor, menor = encontrar_mayor_menor(A, B, C) #se busca el resultado si es mayor o menor 
    print(f"El mayor es: {mayor}") #se busca el valor de la variable 
    print(f"El menor es: {menor}")#se busca el valor de la variable 

![image](https://github.com/user-attachments/assets/8b466e81-e8cc-4767-a3e7-621f3fd4ed45)

![image](https://github.com/user-attachments/assets/5a3aa0e7-69fe-4460-9602-fccef11fa1f1)
