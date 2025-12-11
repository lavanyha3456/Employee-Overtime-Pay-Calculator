# Employee-Overtime-Pay-Calculator

ovpay=0
sum=0
for i in range(1,11):
    print("enter working hours of emp",i,":")
    h=int(input())

    if(h>40):
        extra=h-40
        ovpay=extra*12
        print("overtime pay of emp",i,"is",ovpay)
        sum=sum+ovpay
    else:
        print("no overtime pay")
print("total overtime pay of all employees:",sum)



output:
enter working hours of emp 1 :
50
overtime pay of emp 1 is 120
enter working hours of emp 2 :
7
no overtime pay
enter working hours of emp 3 :
90
overtime pay of emp 3 is 600
enter working hours of emp 4 :
60
overtime pay of emp 4 is 240
enter working hours of emp 5 :
39
no overtime pay
enter working hours of emp 6 :
40
no overtime pay
enter working hours of emp 7 :
50
overtime pay of emp 7 is 120
enter working hours of emp 8 :
60
overtime pay of emp 8 is 240
enter working hours of emp 9 :
30
no overtime pay
enter working hours of emp 10 :
100
overtime pay of emp 10 is 720
total overtime pay of all employees: 2040

