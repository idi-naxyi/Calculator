# Calculator
class Calculator:
    def addition(self):
        print(a + b)
    def subtraction(self):
        print(a - b)
    def multiplication(self):
        print(a * b)
    def division(self):
        print(a / b)
a = int(input("Введите первое число:"))
b = int(input("Введите второе число:"))
v = int (input('Какую операцию вы хотите выполнить? \n 1 Сложение \n 2 Вычитание \n 3 Деление \n 4 Умножение \n'))

if v == 1:
    r = a + b
    p = 'сложения'
    t = p
if v == 2:
    r = a - b
    l = 'вычитания'
    t = l
if v == 3:
    r = float(a / b)
    m = 'деления'
    t = m
if v == 4:
    r = a * b
    n = 'умножения'
    t = n
print ('Результат ',t,' = ',r)
