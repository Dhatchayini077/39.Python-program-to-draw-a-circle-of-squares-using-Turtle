# 39.Python-program-to-draw-a-circle-of-squares-using-Turtle
import turtle
x=turtle.Turtle()
def square(angle):
    x.forward(100)
    x.right(angle)
    x.forward(100)
    x.right(angle)
    x.forward(100)
    x.right(angle)
    x.forward(100)
    x.right(angle+10)
for i in range(36):
    square(90)


OUTPUT:
<img width="331" height="356" alt="24" src="https://github.com/user-attachments/assets/5b9ea62b-d84b-4bc8-bc3c-e2a0e1933a3a" />
