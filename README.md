# assignment
new

for i in range(1,20):
    if (i % 2) == 1:
         sqr_list.append(i*i)
  
 
print(*sqr_list)
1 9 25 49 81 121 169 225 289 361
list = [1,3,5,7,9,11,13,15,17,19]
list1 = []
for x in list:
    list1.append(x*x)
    
    print(list1)
[1]
[1, 9]
[1, 9, 25]
[1, 9, 25, 49]
[1, 9, 25, 49, 81]
[1, 9, 25, 49, 81, 121]
[1, 9, 25, 49, 81, 121, 169]
[1, 9, 25, 49, 81, 121, 169, 225]
[1, 9, 25, 49, 81, 121, 169, 225, 289]
[1, 9, 25, 49, 81, 121, 169, 225, 289, 361]
num = 7
​
if (num % 5) == 0:
    
     print(num, "is a mutiple of 5")
     
           
else:
    print(num, "is not a multiple of 5")
            
    
7 is not a multiple of 5
num = 8
​
if num > 1:
    
    for i in range (2, num):
        if (num % i) == 0:
            print(num, "is not a prime number")
            break
            
        else:
            print(num, "is a prime number")
    
        
8 is not a prime number
my_dict = {
    'age' : 64,
    'car' : 'rolls royce',
    'job' : 'data scientist',
    'home' : 'rubaare'
}
​
#print(list(my_dict.items()))
​
for item in my_dict.items():
    print(item)
('age', 64)
('car', 'rolls royce')
('job', 'data scientist')
('home', 'rubaare')
def add(n1, n2): return n1 + n2
def mult(n1, n2): return n1 * n2
def sub(n1, n2): return n1 - n2
print(mult(54, 23))
1242
opers ={
    "+" = 'add',
    '*' = 'multiply',
    '-' = 'subtract'
​
}
​
print(opers['+'] (44, 55))
  File "C:\Users\USER\AppData\Local\Temp/ipykernel_1636/2039497225.py", line 2
    "+" = 'add',
        ^
SyntaxError: invalid syntax
