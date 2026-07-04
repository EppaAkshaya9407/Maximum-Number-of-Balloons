# Maximum-Number-of-Balloons
from collections import Counter
text=input("Enter the text:")
count=Counter(text)
result=min(count['b'],count['a'],count['l']//2,count['o']//2,count['n'])
print("Maximum number of 'balloon' words:",result)
