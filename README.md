# DSWithPy_A03
30 Hrs add-on course wih python

# Day 1 #

a=20
#a=variable
#20=data
a

print(a)

a="Shruti"
a='Shruti'
a='''Shruti'''
print(a)

a="Shrut"
b="Arsode"
c=a+b
print(c)

print("Shruti\nArsode")

print("Shruti\tArsode")

a=20
type(a)

a="Shruti"
type(a)


# Day 2 #

a=60.2
a

print(a)

type(a)

print('a')
a=30
b=20


b

print(a,b)

a==30

b==30

a=!33
a='Shruti'
len(a)

a='Shruti'
b='Arsode'
c=a+b
c

len(c)

type(c)

a='Ashish@2748'
type(a)
a=2748
type(a)

a=@
type(a)
  
a=20
b=30
c=a+b
print(c)
#Arithmetic Operator

c=b-a
print(c)

c=a*b
print(c)

c=a/b
print(c)

c=b%a
print(c)

a=True
b=False
#Boolean
a&b
#logical

a|b


# Day 2: String #

a='shruti'
a[0]
a[-1]
a[2]
a[-2]
a[0:4]
a[:5]
a[2:]
a.upper()
a.lower()
a.replace('i','u')
a.count('u')
a.find('s')
a.split("t")
x='ashish'
y='a'
print(y in x)
print(x in y)
print(a not in y)


# Day 3:List & its Functions #

#list
l=[10,22.5,'shruti',True]
type(l)

len(l)

#Indexing
l[0]

l[-1]

l[-2]

#Slicing
l[0:3]

l[2:]

l[:3]

l[:2]

l[1:3]
#Changing the index value
l=[10,22.5,'shruti',True]
l[0]=100
print(l)

l

#pop operation
l.pop()

l

l.pop()

l.append('amit')
l

#to reverse the element of list
l=[60,30,90,45,50]
l.reverse()
l

#sorting
l=[60,30,90,45,50]
l.sort()
l

#ascending
l.reverse()
l
#descending
#insert
l.insert(1,'ashish')
1
#concatenate
x=[40,22.5,'shruti']
y=[25,30]
x+y

x,y

#repetation
x*3


# Day 3:Tuple & its Functions #

#Membership operators
x='ashish'
y='a'
print(y in x)

print(y not in x)

#Tuple creation
a=(10,22.5,'shruti',True)
a

print(a)

type(a)

#Indexing 
a[0]
10
a[-1]
True
#Slicing
a[0:3]

a[2:]

a[:2]

a[1:3]

#tuples are immutable
a[2]='Amit'

len(a)

#Concatenation
x=(1,2,3)
y=(4,5,6)
type(x)
tuple
type(y)
tuple
x+y

y+x

#Separator
x,y

y,x

a=(10,'ashish',20,30)
b=(1,2,3,4)
a+b

a,b

#functions of tuple
x=(1,2,3)
min(x)

Min(x)

max(x)

a=('shruti','vaishnavi','sanskruti','kasturi')
min(a)

max(a)

b=('a','b','c','d')
min(b)

max(b)

x=(1,2,3)
#Repeating
x*3


# Day 4:Dictionary #
Dictionary is a part of data structure

d={'ashish':10,'vikram':20,'satish':30,'ajmat':40}
type(d)

len(d)

d

print(d)

#Extracting keys from dictionary
d={'ashish':10,'vikram':20,'satish':30,'ajmat':40}
d.keys()

#Extracting values from dictionary
d={'ashish':10,'vikram':20,'satish':30,'ajmat':40}
d.values()

#Adding a new element
d={'ashish':10,'vikram':20,'satish':30,'ajmat':40}
d['shruti']=50
d

#changing existing element
d={'ashish':10,'vikram':20,'satish':30,'ajmat':40,'shruti':50}
d['ashish']=60
d

#update the dictionary element with another dictionary
d1={'ashish':10,'vikram':20}
d2={'satish':30,'ajmat':40}
d1.update(d2)
print(d1)

d2.update(d1)
print(d2)

#popping element
d={'ashish': 10, 'vikram': 20, 'satish': 30, 'ajmat': 40}
d.pop()
d

d={'ashish': 10, 'vikram': 20, 'satish': 30, 'ajmat': 40}
d.pop('vikram')
d

# Day 4:Set & its Functions #
#set creation 
s={10,22.5,'shruti',True}
s

print(s)

#no duplication
s={10,22.5,'shruti',True,10}
s

len(s)

type(s)

#immutable
s={10,22.5,'shruti',True}
s[0]=30
s

#addition
s={10,22.5,'shruti',True}
s.add('amit')
s

#removal
s={10,22.5,'shruti','amit',True}
s.remove('amit')
s

#update
s={10,20,30}
s.update([1,2,3])
s

#union
s1={1,2,3}
s2={10,20,30}
s1.union(s2)

#intersection
s1={1,2,3}
s2={10,20,30,2}
s1.intersection(s2)

s1={1,2,3}
s2={10,20,30}
s1.intersection(s2)


 # Day 5:Conditional Statements #
if
if else
nested if else
ladder if else
#simple if
a=5
b=3
if(a>b):
    print("a is greater than b")

print("Enter your roll no:")
x=input()
print("Roll no. is "+ x)

#if else
a=3
b=5
if(a<b):
    print("a is less than b",a)
else:
    print("b is less than a",b)    

#if else:user define
a=int(input(print('Enter a value of a: ')))
b=int(input(print('Enter a value of b: ')))
if(a>b):
    print("a is greater than b,",a)
else:
    print("b is greater than a,",b)

 
