@@ ejercicio 1 @@
un metodo python que haga la multiplicacion de 3 numeros
2*4*3 = 24
"""


#start-->
def multiplicacion (a,b,c):
    resultado = a * b * c
    print(resultado)

def multiplica(8,6,4):
    

"""
***************************************************************
@@ ejercicio 2 @@
la suma de los numeros divisibles entre 3 y 5 del 1000 al 2000
"""


# start-->
def sumaDivTresYCincoPlus():
    sum = 0
    for i in range(1000,2001):
        if i % 5 == 0 and i % 3 == 0:
            sum = sum + i
    
    print(sum)
sumaDivTresYCincoPlus()


"""
***************************************************************
@@ ejercicio 3 @@
encontrar el area y el volumen de un ortoedro
longitud = 10 m
latitud = 6 m
altura = 5 m
area: A = 2(longitud · latitud + longitud · altura + latitud · altura)
volumen: V = longitud · latitud · altura
"""


# start-->
def definicionOrtoedro():
    lon = 10
    lat = 6
    alt = 5
    Area = 2*((lon*lat)+(lon*alt)-(alt+lat*alt))
    Volumen = lon*lat*alt
    
    print("el area es: ",Area)
    print("el volumen es: ",Volumen)



"""
***************************************************************
@@ ejercicio 4 @@
el ejercicio numero 3 convertirlo en una clase
"""


# start-->
class Ortoedro:
    def definicionOrtoedro(self, longitud, latitud, altitud):
        self.longitud = lon 
        self.lat = lat
        self.altitud = alt
    
    def Volumen(10,6,5):
        Volumen = lon*lat*alt
        print(Volumen)
    
    def area(10,6,5):
        Area = 2*((lon*lat)+(lon*alt)-(alt+lat*alt))
        print(Area)


"""
***************************************************************
@@ ejercicio 5 @@
VentaComputadoras
Computadora
    procesador
    ram
    tarjeta_grafica
    ssd
    costo
    conDescuento
    descuento
    conPlazo
    cuota
"""


class VentaComputadoras:
    def orden(self):
        pass

    def totalProcesadorIntel(self):
        return 0

    def totalRam16ConDescuento(self):
        return 0


class Computadora:
    pass


"""
***************************************************************
@@ ejercicio 6 @@
colocar este proyecto en github
colocar aca debajo la url
ademas colocar la url en un archivo
github_<nombre>_<codigo>.txt y subirlo a moodle
"""
