## Соколова Анна

##### Компетенции в IT-сфере:
* MS Office
* GIMP
* C
* Python

##### Ссылка на портфолио:

https://github.com/calabiyauspace/portfolio

##### Mотивирующая картинка:

![pic][sleepycowboi]

[sleepycowboi]: https://pbs.twimg.com/media/EE4r3ZhUwAA-Hy8?format=png&name=small "sleepycowboi"

##### Решение задачи:

```python
import math

a = int(input("Введите a: "))
b = int(input("Введите b: "))
c = int(input("Введите c: "))

def S():
  p = (a + b + c) / 2
  return math.sqrt(p * (p - a) * (p - b) * (p - c))

print("Площадь треугольника: ", S())

#тест #1
def test_S():
    assert S() == 6, "S = 6"
    #проверяем при a=3, b=4, c=5
    
if __name__ == "__main__":
    test_S()
    print("IT'S ALIVE")
```
