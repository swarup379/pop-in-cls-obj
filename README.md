class number():
    even=[]
    odd=[]
    def __init__(self,num):
        self.num=num
        if(num%2==0):
            number.even.append(num)
        else:
            number.odd.append(num)
    number.even.pop(0)
    number.odd.pop(1)
    print(number.even)
    print(number.odd)
num1=number(21)
num2=number(79)
num3=number(46)
num4=number(96)
num5=number(65)
