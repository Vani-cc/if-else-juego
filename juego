# Importamos la librería random para que la computadora elija de manera aleatoria
import random

# Definimos la función principal del juego
def piedra_papel_tijera():
    # Opciones que la computadora puede elegir
    opciones = ["piedra", "papel", "tijera"]

    # Imprimimos un mensaje de bienvenida
    print("¡Bienvenido al juego Piedra, Papel o Tijera!")
    print("Elige entre piedra, papel o tijera.")

    # Pedimos al jugador que elija una opción
    eleccion_jugador = input("¿Cuál es tu elección? (piedra, papel, tijera): ").lower()

    # Verificamos si la elección del jugador es válida
    if eleccion_jugador not in opciones:
        print("Elección inválida. Por favor, elige entre piedra, papel o tijera.")
        return  # Salimos de la función si la elección es inválida

    # La computadora elige aleatoriamente
    eleccion_computadora = random.choice(opciones)

    # Imprimimos las elecciones de ambos
    print(f"Tú elegiste: {eleccion_jugador}")
    print(f"La computadora eligió: {eleccion_computadora}")

    # Comprobamos quién gana con las reglas del juego
    if eleccion_jugador == eleccion_computadora:
        print("¡Es un empate!")
    elif (eleccion_jugador == "piedra" and eleccion_computadora == "tijera") or \
         (eleccion_jugador == "papel" and eleccion_computadora == "piedra") or \
         (eleccion_jugador == "tijera" and eleccion_computadora == "papel"):
        print("¡Ganaste!")
    else:
        print("¡Perdiste! La computadora gana.")

# Llamamos a la función para iniciar el juego
piedra_papel_tijera()
