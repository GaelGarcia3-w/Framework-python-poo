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



