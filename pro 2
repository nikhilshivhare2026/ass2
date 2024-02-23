def factorial(n):
    if n == 0 or n == 1:
        return 1
    else:
        return n * factorial(n - 1)


numbers = [int(x) for x in input("Enter numbers separated by spaces: ").split()]


factorials = [factorial(num) for num in numbers]
print(','.join(map(str, factorials)))
