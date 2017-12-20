def add(x, y):
  return x + y 
def sub(x, y):
  return x + y 
def mul(x, y):
  return x * y
def div(x, y): 
  return x / y
  
print("Select operation.")  
print("1.Add")  
print("2.Sub")  
print("3.Mul")  
print("4.Div") 
choice = input("(1/2/3/4):")  
num1 = int(input(" first number: "))  
num2 = int(input(" second number: "))  
  
if choice == '1':  
   print(num1,"+",num2,"=", add(num1,num2))  
  
elif choice == '2':  
   print(num1,"-",num2,"=", subtract(num1,num2))  
  
elif choice == '3':  
   print(num1,"*",num2,"=", multiply(num1,num2))  
elif choice == '4':  
   print(num1,"/",num2,"=", divide(num1,num2))  
else:  
   print("invalid")
