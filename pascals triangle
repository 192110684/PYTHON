rows = int(input("Enter number of rows: "))
coef = 1

for i in range(1, rows+1):
    for space in range(1, rows-i+1):
        print(" ",end="")
    for j in range(0, i):
        if j==0 or i==0:
            coef = 1
        else:
            coef = coef * (i - j)//j
        print(coef, end = " ")
    print()
>>>> output:-
Enter number of rows: 5
    1 
   1 1 
  1 2 1 
 1 3 3 1 
1 4 6 4 1 
