# python
A collection of attempts and (hopefully) solutions to the problems presented on https://projecteuler.net in various programming languages.

#Finding the multiples of 3 & 5

def ProblemOne(n):
    total = 0
    while n > 0:
        if n % 3 == 0 or n % 5 == 0:
            total += n
            n -= 1
        else:
            n -= 1
    return total
		
