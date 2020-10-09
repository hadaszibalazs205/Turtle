import turtle
wn = turtle.Screen()
alex = turtle.Turtle()

def sokszog(szogekszama, hossz, szin):

    for i in range(szogekszama):
        alex.color(szin)
        alex.forward(hossz)
        alex.left(360/szogekszama)
        
sokszog(5, 10, "red")
sokszog(5, 20, "green")
sokszog(5, 30, "blue")
sokszog(5, 40, "brown")
sokszog(5, 50, "yellow")
sokszog(5, 60, "black")
