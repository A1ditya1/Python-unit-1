# Python-unit-1
programs in unit 1
  
  
1) Program to print hello world.
for i in range(0,7):
  if(i%2!=0):
    break
  print("%d)hello world"%i)
  
  
 2) Programs to print the details of a student
student = {"name":"Aditya","branch":"ECE"}
print(student)
print(student["name"])
#print(student["branch"])



3) program  to get the largest between 3 numbers
x = (int)(input("enter the number 1:"))
y = (int)(input("enter the number 2:"))
z = (int)(input("enter the number 3:"))
if x>y and y>z :
  print("x is the greatest")
elif y>z and y>x :
  print("y is the greatest")
else :
  print("z is the greatest")
  
   
  4) Program to get the grade for the respective marks scored
  marks = (int)(input("enter the marks:"))
if marks<=100 and marks>=90:
  print("you got an O grade")
elif marks<=89 and marks>-80:
  print("you got an A grade")
elif marks<=79 and marks>=70:
  print("you got an A1 grade")
elif marks<=69 and marks>=60:
  print("you got an B grade")
elif marks<=59 and marks>=50:
  print("you got an C grade")
elif marks<=49 and marks>=40:
  print("you got an D grade")
else :
  print("you got an F grade")
  
  
  
  
  
5)
