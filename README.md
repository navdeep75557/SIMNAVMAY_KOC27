# SIMNAVMAY_KOC27
#to cut the cake in the given way 
def cutCake(n):
    #case1
    if(360 % n==0):
        print("1",end="")
    else: 
        print("0",end="");
    
    #case2
    if(n<=360):
        print("1",end="")
    else:
        print("0",end="");
    
    #case3
    if(((n*(n+1))/2)<=360):
        print("1",end="")
    else:
        print("0",end="");
#code
n=7;
cutCake(n);
