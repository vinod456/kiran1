#palindrome
str=input("enter a string:")
if str ==str[::-1]:
    print "palindrome"
else:
    print "not palindrome"

# second smallest number in list
list=[]
num=input("enter number of elements:")
for n in range(num):
    number=int(input("enter number:"))
    list.append(number)
list.sort()
print "second smallest element:", list[1]

#SUM OF LIST OF NUMBERS
list=[]
num=input("enter number of elements:")
for n in range(num):
    number=int(input("enter number:"))
    list.append(number)
print "sum of list numbers:",sum(list)

# count the number of capital letters in string
import re
string = "Not mAnY Capital Letters"
len(re.findall(r'[A-Z]',string))

#READ RANDOM LINE FROM FILE
import random
def random_line(fname):
    lines=open(fname).read().splitlines()
    return random.choice(lines)
print(random_line('sample2.txt'))


