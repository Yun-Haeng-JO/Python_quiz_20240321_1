# Python_quiz_20240321_1



짝수만 필터링해서 출력하는 코드

numbers = [111, 26, 37, 48]
result = list(filter(lambda x: x % 2 == 0, numbers))
print(result)

=======

# Python_quiz_20240321_2

numbers = [111,26,37,48]
result = []
for num in numbers:
    if num % 2 == 0:
        result.append(num)
print(result)

numbers = [111,26,37,48]
result = list(filter(lambda x: x % 2 == 0, numbers))
print(result)
