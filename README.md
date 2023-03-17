#P2 calculator
 
 
a=float(input("Enter a number :"))
c=input("Choose the operator to use   Multiply(*), Division(/), Addition(+), Substraction=(-)    :")
b=float(input("Enter another number:"))
 
 
 
if c=="*":
  print("The product of",a,"and",b, "is   :" ,a*b)
elif c=="/":
  print("The quotient of",a, "and",b, "is   :",a/b)
elif c=="+":
  print("The Sum of",a ,"and",b ,"is   :",a+b)
elif c=="-":
  print("The Difference between",a ,"and",b ,"is   :",a-b)
else:
  print("Enter a valid input.")
