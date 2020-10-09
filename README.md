import turtle
wn = turtle.Screen()
alex = turtle.Turtle()

def sokszog(szogekszama, hossz, szin):

    for i in range(szogekszama):
        alex.color(szin)
        alex.forward(hossz)
        alex.left(360/szogekszama)
        
 sokszog(5, 25, *red*)
 sokszog(10, 50, *green*)
 sokszog(15, 75, *blue*)
