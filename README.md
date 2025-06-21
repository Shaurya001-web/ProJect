# ProJect:FIzzBuzz qs of leet code
def fizzBuzz(i):
    result = []
    for n in range(1, i + 1):
           if n % 3 == 0 and n % 5 == 0:
                result.append("FizzBuzz")
           elif n % 3 == 0:
               result.append("Fizz")
           elif n % 5 == 0:
                result.append("Buzz") 
    else:
        result.append(str(n))
    return  result
