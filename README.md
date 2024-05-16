texto = str(input("Ingrese un texto: "))
palabras = texto.split(" ")
if(len(palabras)%2==0 and len(palabras)%3==0):
    print("La cantidad de palabras que tiene el texto es igual a "+str(len(palabras)+", y la cantidad de caracteres que tiene el texto es igual a "+str(len(texto))+".")
elif(len(palabras)%2==0):
    print("La cantidad de caracteres que tiene el texto es igual a "+str(len(texto))+".")
elif(len(palabras)%3==0):
    print("La cantidad de palabras que tiene el texto es igual a "+str(len(palabras))+".")
else:
    print("La cantidad de caracteres del texto multiplicada por 10 es igual a "+str(len(texto)*10)+".")
