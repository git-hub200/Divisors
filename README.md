# Divisors
n=int(input("Enter a Number: "))
div=[]

for i in range(1,n+1):
    if n%i==0:
        div.append(i)
str_div=",".join(map(str,div))
print(f"Divisors of {n} are {str_div}")
