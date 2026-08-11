# CANLAS-ARVIN-2B-08-11-26
https://www.programiz.com/online-compiler/2NT1jP8dgBgNJ

class Comparator:
    def compare_three_numbers(self):
        num1 = float(input("Enter your first number: "))
        num2 = float(input("Enter your second number: "))
        num3 = float(input("Enter your third number: "))

        if num1 >= num2 and num1 >= num3:
            print("num1 is the biggest number")
        elif num2 >= num1 and num2 >= num3:
            print("num2 is the biggest number")
        else:
            print("num3 is the biggest number")


obj = Comparator()
obj.compare_three_numbers()
