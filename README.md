# par-o-impar-alan-reyes
mi código para saber si es par o impar el numero
# INFO DE PROGRAMADOR Y PRACTICA

print ("REYES MEZA ALAN EDUARDO 3W :  par, impar o 0") #NOMBRE PRACTICA Y DATOS DE PROGRAMADOR"

print (" ") #ESPACIO PARA AGREGAR LA INFO DE PRACTICA Y PROGRAMADOR
# Función que verifica si un número es par, impar o cero

def verificar_numero(num):
   
    """Retorna una cadena que indica si el número es par, impar o cero."""
   
    if num == 0:
      
        return "El número es cero."
    
    return "El número es par." if num % 2 == 0 else "El número es impar."

# Solicitar al usuario que ingrese un número

try:
   
    numero_usuario = int(input("Ingresa un número: "))
   
    print(verificar_numero(numero_usuario))

except ValueError:
  
    print("Por favor, ingresa un número entero válido.")

![image](https://github.com/user-attachments/assets/112d0aa3-6a28-49ed-be22-59a9fcc5cd4a)



