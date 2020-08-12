# pyt
code for fibonacci numbers 


def Fibonacci(n): 

    if n<0: 
    
        print(" not correct input")
        
    else if n==1: 
    
        return 0
        
    else if n==2: 
    
        return 1
        
    else:
    
        return Fibonacci(n-1)+Fibonacci(n-2)
        
        print(fibonacci(5))
