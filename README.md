 # (1) program to print the pattern below way
1 1 1 1 1 
2 2 2 2 2 
3 3 3 3 3 
4 4 4 4 4 
5 5 5 5 5 
------------------------------
n =int(input("enter the number"))
for i in range(1,n+1,1):
    for j in range(1,n+1,1):
        print(i,end=' ')
    print()
 ---------------------------------
 # (2) program to print the below pattern
1 2 3 4 5 
1 2 3 4 5 
1 2 3 4 5 
1 2 3 4 5 
1 2 3 4 5 
---------------------------------------
n =int(input("enter the number"))
for i in range(1,n+1,1):
    for j in range(1,n+1,1):
        print(j,end=' ')
    print()
--------------------------------------
   #(3)programtoprintthebelowpattern
5 5 5 5 
4 4 4 4 
3 3 3 3 
2 2 2 2 
1 1 1 1 
0 0 0 0 
n =int(input("enter the number"))
for i in range(n,-1,-1):
    for j in range(1,n,1):
        print(i,end=' ')
    print()
