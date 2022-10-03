rows = int(input("Enter the Number of rows : " ))
column = int(input("Enter the Number of Columns: "))

print("Enter the elements of First Matrix:")
matrix_a= [[int(input()) for i in range(column)] for i in range(rows)]
print("First Matrix is: ")
for n in matrix_a:
    print(n)

print("Enter the elements of Second Matrix:")
matrix_b= [[int(input()) for i in range(column)] for i in range(rows)]
for n in matrix_b:
    print(n)
    
result=[[0 for i in range(column)] for i in range(rows)]

for i in range(rows):
    for j in range(column):
        result[i][j]= matrix_a[i][j]+matrix_b[i][j]

print("The sum of Above two Matrices is : ")
for r in result:
    print(r)
>>>> output:-
Enter the Number of rows : 2
Enter the Number of Columns: 3
Enter the elements of First Matrix:
5
6
7
4
8
9
First Matrix is: 
[5, 6, 7]
[4, 8, 9]
Enter the elements of Second Matrix:
1
3
1
1
1
3
[1, 3, 1]
[1, 1, 3]
The sum of Above two Matrices is : 
[6, 9, 8]
[5, 9, 12]
