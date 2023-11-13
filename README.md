# calculator
x = float(input('Введите первое число: '))
operator = input('Введите оператор: (+, -, *, /,): ')
y = float(input('Введите второе число: '))
if operator == '+':
    result = x + y
elif operator == '-':
    result = x - y
elif operator == '*':
    result = x * y
elif operator == '/':
    if y == 0:
        print('Ошибка: деление на ноль!')
        exit()
    result = x / y
else:
    print('Ошибка: неверный оператор!')
    exit()


  print('Результат:', result)
