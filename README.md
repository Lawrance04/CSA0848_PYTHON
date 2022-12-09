print("DIWALI BONUS ")
sex=input("ENTER THE GENDER MALE or FEMALE =")
if (sex=='male'):
    print("5% bonus ")
    b=5
else :
    print("10% bonus")
    b=10
salary=int(input("ENTE THE BASIC PAY SALARY :"))
if salary >= 10000:
    print("NO  EXTRA BONUS ")
    bonusSalary=(b/100)*salary
else :
    print("EXTRA 2% BONUS ")
    bonusSalary=(b+2/100)*salary
print("BASIC PAY =",salary)
print("TOTAL BONUS SALARY AMOUNT =",bonusSalary)
