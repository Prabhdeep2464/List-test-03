# List-test-03
## Question6
### Prabhdeep singh
```
students=[]
n1=input("Enter first name:")
n2=input("Enter second name:")
n3=input("enter third name:")
n4=input("enter fourth name:")
n5=input("enter fifth name:")
students.append(n1)
students.append(n2)
students.append(n3)
students.append(n4)
students.append(n5)
print(students)
print(students[0:1])
print(students[-1:-2:-1])
print(len(students))
```
## Question7
```
students.append("Ranvir")
students.insert(1,"Rajveer")
students.remove("Ranvir")
students.sort()
print(students)
```
## Question8
```
m1=eval(input("Enter students marks of first subject:"))
m2=eval(input("Enter students marks of second subject:"))
m3=eval(input("Enter students marks of third subject:"))
total_marks=m1+m2+m3
print(total_marks)
average_marks=total_marks/3
print(average_marks)
percentage=(total_marks/300)*100
print(percentage)
if percentage>=40:
  print("Passed")
else:
  print("Failed")
```
## Question9
```
t=("Python","Axel","Power BI","AI","SQL")
y=list(t)
print(y)
print(y[0:1],y[-1:-2:-1])
print(len(y))
print("Python" in y)
```
## Question10
```
mb={"Aman","Simran","Rahul","Priya"}
eb={"Rahul","Karan","Simran","Neha"}
q=mb.union(eb)
p=eb.intersection(mb)
print(q.difference(p))
print(mb.intersection(eb))
print(mb.difference(eb))
print(eb.difference(mb))
print(len(q.difference(p)))
```
## Output
```
Enter first name:Rajvir
Enter second name:Inderjeet
enter third name:Kamal
enter fourth name:Gurlove
enter fifth name:Manjinder
['Rajvir', 'Inderjeet', 'Kamal', 'Gurlove', 'Manjinder']
['Rajvir']
['Manjinder']
5


['Gurlove', 'Inderjeet', 'Kamal', 'Manjinder', 'Rajveer', 'Rajvir']
Enter students marks of first subject:90
Enter students marks of second subject:90
Enter students marks of third subject:90
270
90.0
90.0


Passed
['Python', 'Axel', 'Power BI', 'AI', 'SQL']
['Python'] ['SQL']
5
True
{'Karan', 'Priya', 'Aman', 'Neha'}
{'Simran', 'Rahul'}
{'Priya', 'Aman'}
{'Karan', 'Neha'}
4
```







