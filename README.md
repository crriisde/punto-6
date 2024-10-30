print (" ") #este linea deja el espacio para el nombre 
print ("Cristian David Salas De La O 3,W") #este linea define el nombre del programador 
print (" ") #este linea defa el espacio para el nonbre 
# Crear un archivo y sobrescribir el contenido
with open("demofile3.txt", "w") as f: #este linea define el with 
    f.write("¡Woops! He eliminado el contenido.\n") #este linea define el contenido 

# Leer el archivo después de sobrescribir
with open("demofile3.txt", "r") as f:  #este linea define le with 
    print("Contenido de demofile3.txt:")  #este linea define le contenido del demofil 
    print(f.read())  #este linea muestra lo final 
![image](https://github.com/user-attachments/assets/b08a8776-c8c6-443a-9614-120db525a432)
![image](https://github.com/user-attachments/assets/2acd4223-0471-4fd3-931f-11db89558905)
