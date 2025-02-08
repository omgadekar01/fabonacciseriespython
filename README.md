# fabonacciseriespython
 GENERATE FABBONACCI SERIES USING PYTHON
n = int(input("Enter the number of terms: "))
a=0
b=1
c=0
print("Fibonacci Series:")
for series in range(n):
    print(a)
    c=a+b
    a=b
    b=c
