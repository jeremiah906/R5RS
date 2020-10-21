# R5RS

The map() function applies a function to every member of an iterable and returns the result. Lambda is a single expression anonymous function often used as an inline function. Lambda can be used inside a list and dictionary.

The fib_list which is taken already has 0 and 1. Then in the next iteration, this will be used as input, and the result of their sum will append to the list.

def fibonacci(number): 
    fib_list = [0, 1] 
  
    any(map(lambda _: fib_list.append(sum(fib_list[-2:])), 
                                         range(2, count))) 
  
    return fib_list[:number] 
  
print(fibonacci(10))  // 10 is the input which we want to give
