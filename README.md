# Trabajo-icc
def main():
    print("¿Es la primera vez que recorres estas tierras?")
    print(" ")
    print("1: Sí")
    print("0: No")
    print(" ")
    respuesta=input("->  ")
    if respuesta=="1" or respuesta=="si" or respuesta=="Sí" or respuesta=="sí":
        usuario_nuevo()
    else:
        select_menu()

def usuario_nuevo():
    print(" ")
    print("¡Oh!")
    print(" ")
    print("Presione “enter” para continuar...")
    tecla = input()
    print("Tú no eres de por aquí...")
    tecla = input()
    print("Hace mucho tiempo que no teníamos un extranjero.")
    tecla = input()
    print("¿Qué te trae por aquí?")
    tecla = input()
    print("Ya veo...")
    tecla = input()
    print("¡Siempre estamos felices de tener visitantes!")
    tecla = input()
    print("Ya que es tu primera vez aprendiendo python, empecemos con algunos conceptos:")
    print(" ")
    print(" ")
    tecla = input()
    variables()
    print(" ")
    print(" ")
    tecla = input()
    estructuras_control()
    print(" ")
    print(" ")
    tecla = input()
    listas()
    print(" ")
    print(" ")
    tecla = input()
    funciones()
    print(" ")
    print(" ")
    tecla = input()
    strings()
    print(" ")
    print(" ")
    tecla = input()
    final()
    
    
def select_menu():
    print(" ")
    print("¡Oh! Ya recuerdo...")
    print(" ")
    print("Presione “enter” para continuar...")
    tecla = input()
    print("¿Qué castillo deseas visitar?")
    print(" ")
    print("1: Castillo de las VARIABLES")
    print("2: Castillo de las ESTRUCTURAS DE CONTROL")
    print("3: Castillo de las LISTAS")
    print("4: Castillo de las FUNCIONES")
    print("5: Castillo de los STRINGS")
    print(" ")
    tema=input("->  ")
    if tema=="1":
        variables()
        print(" ")
        print(" ")
        tecla = input()
        estructuras_control()
        print(" ")
        print(" ")
        tecla = input()
        listas()
        print(" ")
        print(" ")
        tecla = input()
        funciones()
        print(" ")
        print(" ")
        tecla = input()
        strings()
        print(" ")
        print(" ")
        tecla = input()
        final()
    elif tema=="2":
        estructuras_control()
        print(" ")
        print(" ")
        tecla = input()
        listas()
        print(" ")
        print(" ")
        tecla = input()
        funciones()
        print(" ")
        print(" ")
        tecla = input()
        strings()
        print(" ")
        print(" ")
        tecla = input()
        final()
    elif tema=="3":
        listas()
        print(" ")
        print(" ")
        tecla = input()
        funciones()
        print(" ")
        print(" ")
        tecla = input()
        strings()
        print(" ")
        print(" ")
        tecla = input()
        final()
    elif tema=="4":
        funciones()
        print(" ")
        print(" ")
        tecla = input()
        strings()
        print(" ")
        print(" ")
        tecla = input()
        final()
    elif tema=="5":
        strings()
        print(" ")
        print(" ")
        tecla = input()
        final()
    else:
        print("error No conozco ningún castillo con ese nombre...Por favor reinicia el programa.")

def variables():
    print(" ")
    print("Bienvenido al castillo Variable")
    print("  ")
    print("En este castillo aprenderás sobre las Variables")
    print("  ")
    print("Las variables, son etiquetas que ocupan un espacio de memoria la cual se utiliza para la almacenar esta data. ")
    print("estas pueden tomar valores de números, frases, e incluso operaciones aritméticas de más variables. Además, aprenderá a como hacer que un")
    print("usuario le asgine a traves de un programa un valor a una variable")
    print("  ")
    print(" Para seguir aprendiendo presione cualquier tecla: ")
    x = input()
    print("  ")
    print(mundo_variables_valores())  # Aqui poner informacion de definicion y la nomenclatura de valores int string y float
    print(mundo_variables_operadores())  # poner las operaciones aritméticas básicas como sumas etc, y  e import math
    print(mundo_variables_funciones())  # como hacer inputs enmascarar y como utilizarlo con variables(ex: hallar el promedio de altura de 3 amigos)

def mundo_variables_valores():
    print(" Para aprender a utilizar Variables primero utilizaremos un ejemplo:" )
    print(" En este ejemplo utilizaremos la variable x:" )
    x=3
    print("x = 3")
    print(" Esta variable x ahora va a tener un valor de 3" )
    print("  " )
    print(" Para continuar presione cualquier tecla" )
    x = input()

    print(" Las variables pueden tomar  3 formas principales, números enteros, conocidos como 'integers', abreviados int; números decimales, conocidos como 'floats', y texto conocido como string")
    print(" Por ejemplo, variables con este tipo de valores : X=3, W= hola, F=7.6" )
    print(" Las variables, como se vera más adelante, serviran para almacenar información la cual se puede utilizar en operaciones matemáticas." )
    print(" Es importante saber que los valores entre las Categorias presentadas (string e integers) no pueden sumarse ni operarse, ya que uno se entiende como texto y otro como numero" )

    print(" Para continuar presione cualquier tecla" )
    x = input()
    print(mundo_variables_valores_ejericios())
