# Función para elevar un número al cubo

def elevar_al_cubo(numero):
    """
    Esta función recibe un número y devuelve su cubo.
    Ejemplo: 3 → 27
    """
    return numero ** 3  # El operador ** eleva a la potencia

# Programa principal
if __name__ == "__main__":
    # Pedimos un número al usuario
    num = float(input("Ingresa un número: "))

    # Llamamos la función y mostramos el resultado
    resultado = elevar_al_cubo(num)

    print(f"El número {num} elevado al cubo es: {resultado}")
