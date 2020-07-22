 """"Ejercisio 3 de la semana pasada""""
     
Frutas = {'Durazno':1.30, 'Manzana':5.0, 'Pera':4.5, 'Uva':4.0}
Fruta = input('¿Qué fruta quieres? ').title()
kg = float(input('¿Cuántos kilos? '))
if Fruta in Frutas:
    print(kg, 'kilos de', Fruta, 'valen', Frutas[Fruta]*kg )
else: 
    print("Lo sentimos, la fruta", Fruta, "no se encuentra disponible.")
    
    
    
      """"Ejercisio 2 de esta semana""""


lista = [1, 2, 3, 4, 5]
try:
    lista[10]
except IndexError:
    print("Error:\tEl índice se encuentra fuera del rango,\n"
          "\tdebes utilizar un número mayor o igual que cero\n"
          "\ty menor que la longitud de la lista.")
