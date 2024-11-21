# Framework-python-poo
Edgar Gael Garcia Camacho 3-W

# #1
class Persona:

  def __init__(self, nombre="", edad=0, dni=""):
  
  self.nombre = nombre
  
  self.edad = edad
  
  self.dni = dni

  def mostrar(self):

  return f"Nombre: {self.nombre}, Edad: {self.edad}, DNI: {self.dni}"

  def esMayorDeEdad(self):

  return self.edad >= 18


#Ejemplo de uso
if __name__ == "__main__":

  persona = Persona("Edgar Gael", 16, "230802412")
  
  print(persona.mostrar())

  print("Mayor de edad:", persona.esMayorDeEdad())

![image](https://github.com/user-attachments/assets/c2d68470-7bb7-424d-bd40-6498be2d27d8) ![image](https://github.com/user-attachments/assets/f4b24710-d710-4ee3-9419-0defb118c17e)

# #2

#Clase Persona

class Persona:

  def __init__(self, nombre, edad, dni):
  
  self.nombre = nombre
  
  self.edad = edad
  
  self.dni = dni

  def mostrar(self):

  return f"Nombre: {self.nombre}, Edad: {self.edad}, DNI: {self.dni}"


#Clase Cuenta

class Cuenta:

def __init__(self, titular, cantidad=0):

  self.titular = titular
  
  self.cantidad = cantidad

  def mostrar(self):

  return f"Titular: {self.titular.mostrar()}, Cantidad: {self.cantidad}"

  def ingresar(self, cantidad):

  if cantidad > 0:
  
  self.cantidad += cantidad

  def retirar(self, cantidad):

  self.cantidad -= cantidad



#Ejemplo de uso

if __name__ == "__main__":

#Crear una persona para usar como titular
 
  persona = Persona("Gael Garcia", 20, "23080214")

  #Crear una cuenta

  cuenta = Cuenta(persona, 1000)
  
  print(cuenta.mostrar())
  
  cuenta.ingresar(700)
  
  cuenta.retirar(400)
  
  print(cuenta.mostrar())

![image](https://github.com/user-attachments/assets/a76b4a5a-d94b-492d-9707-1e9a411173b3) ![image](https://github.com/user-attachments/assets/e56c5cb3-ae11-4b39-8e6a-0bdd5cd9f190)

