# Archivos-de-texto
Archivos de texto
# Escritura de archivo de texto
with open("my_notes.txt", "w") as archivo:
    archivo.write("Nota 1: Estudiar para el examen de matemáticas.\n")
    archivo.write("Nota 2: Terminar el informe de TIC.\n")
    archivo.write("Nota 3: Practicar programación en Python.\n")

# Lectura de archivo de texto
with open("my_notes.txt", "r") as archivo:
    print("Contenido del archivo my_notes.txt:")
    for linea in archivo:
        print(linea.strip())  # .strip() elimina los saltos de línea

# No es necesario cerrar manualmente el archivo cuando se usa 'with', 
# se cierra automáticamente al salir del bloque.

