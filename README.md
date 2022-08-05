# laboratorio2
class lavadora:
    modelo="LG"

    __color="blanca"
    __peso=50
    __marca="marca"
    __encendido="False"
    __tamano=20
    __girar="girar"


    def __init__(self,marca,color):
        self.__color=color
        self.__marca=marca
        self.__peso=50
        self.__encendido="False"
        self.__tamano=20
        self.__girar="girar"

    def encendido(self,encender):
        self.__encendido=encender

        if self.__encendido:
            return "La lavadora está encendida"

        else:
            "La lavadora esta Apagada"

    def lavar(self,girar):
        self.__girar=lavar


mi_electrodomestico=lavadora("LG","blanca")
print (mi_electrodomestico.encendido(True))
