# 1
numbers_1 = input("Введите числа через пробел: ")
# input = "56 74 321 2 5849 34 367 29 432"
list = list(map(int, numbers_1.split(" ")))

# 2
list.sort()

# 3
numbers_2 = int(input("Введите любое число: "))
maxValue = 0
for i in list:
    if i < numbers_2:
        maxValue = i

def binary_search(array, element, left, right):
    if left > right:
        return False

    middle = (right + left) // 2
    if array[middle] == element:
        return middle
    elif element < array[middle]:

        return binary_search(array, element, left, middle - 1)
    else:
        return binary_search(array, element, middle + 1, right)


print(binary_search(list, maxValue, 0, len(list) - 1))
