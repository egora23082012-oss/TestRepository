# TestRepository

## Простой код на Python

### Рисунок с помощбю черепашки:

```
import turtle
import random

t = turtle.Turtle()
t.speed(0)  # Fastest speed

# Generate random colors
colors = ["red", "blue", "green", "purple", "yellow", "orange"]

for i in range(50):
    t.color(random.choice(colors))
    t.circle(i * 5)
    t.left(20)

turtle.done()
```

<img width="1024" height="491" alt="image" src="https://github.com/user-attachments/assets/ea2f0184-766f-4036-be9e-74f396f76128" />

### Что должно получиться

Это тестовый репозиторий для тестирования платформы
