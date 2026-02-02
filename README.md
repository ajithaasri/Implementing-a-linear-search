# Implementing a Linear Search

numbers = [4, 2, 7, 1, 8, 3, 6]

f = 0  # flag
x = int(input("Enter the number to be found out: "))

for i in range(len(numbers)):
    if x == numbers[i]:
        print("Successful search, the element is found at position", i)
        f = 1
        break

if f == 0:
    print("Oops! Search unsuccessful")
    
OUTPUT:

Enter the number to be found out: 7
Successful search, the element is found at position 2

Enter the number to be found out: 9
Oops! Search unsuccessful
