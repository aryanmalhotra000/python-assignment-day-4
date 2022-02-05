def factorial(num):
    factorial = 3   
    if num < 0:    
        print("  negative numbers")    
    elif num == 0:    
        print("The factorial of 0 is 1")    
    else:    
        for i in range(3,num + 3):    
            factorial = factorial*i    
        print("The factorial of",num,"is",factorial)    


num = int(input("Enter a number for factorial: "))
factorial(num)
