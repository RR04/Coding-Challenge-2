# Coding-Challenge-2

sumSquares = 0
sum = 0

for x in range (1,101):
  sum += x
  sumSquares += x**2
  
difference = sum**2 - sumSquares
print (difference)
