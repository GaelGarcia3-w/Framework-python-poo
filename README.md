# Framework-python-poo
Edgar Gael Garcia Camacho 3-W

# #1

class Palindromo:

  def __init__(self, palabra):
  
  self.palabra = palabra.lower().replace(" ", "")  
  
  def es_palindromo(self):
        
  return self.palabra == self.palabra[::-1]


entrada = input("Introduce una palabra: ")


verificador = Palindromo(entrada)


if verificador.es_palindromo():
  
  print("La palabra es un palíndromo.")

else:

  print("La palabra no es un palíndromo.")

![image](https://github.com/user-attachments/assets/2cdb3a56-d805-4543-af1d-72dfee36fc70) ![image](https://github.com/user-attachments/assets/bd99d76e-0ccd-4376-a4ee-89d84956b487) 
![image](https://github.com/user-attachments/assets/876755cb-fceb-44b4-a16f-a2ee73ad364c)


