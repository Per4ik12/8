# 8

N = int(input())
while N < 1 or N > 10000:
    print("Количество чисел должно быть в диапазоне от 1 до 10000. Попробуйте еще раз.")
    N = int(input())

numbers = []

for _ in range(N):
    num = int(input())
    numbers.append(num)

reversed_numbers = numbers[::-1]

for num in reversed_numbers:
    print(num)
