n = int(input("Masukkan nilai n: "))

if n < 2:
    print( n , "bukan bilangan prima")
i = 2
while i < n:
    if n % i == 0:
         print( n , "bukan bilangan prima")
         break
    i += 1
else:
    print( n , "adalah bilangan prima")
