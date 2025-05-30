class AreaRectangulo: #La clase, [Como ya tenemos una clase las def, se vuelven metodos]
    def __init__(self, base, altura): #Constructor de la clase

        self.base = base #Aqui es donde esta el objeto y su identificador
        self.altura = altura

    def calcular_area(self): #Metodo para calcular el area del rectangulo

        return self.base * self.altura
    
if __name__ == "__main__": # se interactúa con el usuario para obtener las dimensiones

    try:
        base_rect = input("\nIngrese la base del rectangulo: ")
        base_rectangulo = float(base_rect)
        altura_rect = input("\nIngrese la altura del rectángulo: ")
        altura_rectangulo = float(altura_rect)
    except ValueError:
        print("\nEntrada inválida. Por favor, ingrese números validos")
        exit()

    mi_rectangulo = AreaRectangulo(base_rectangulo, altura_rectangulo) # Crear un objeto de la clase Rectangulo

    area_calculada = mi_rectangulo.calcular_area() # Calcula el área utilizando el método del objeto

    print(f"\nEl área del rectángulo es de: {area_calculada}" " cm")
