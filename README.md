# python_upskill_YURY
#  Требуется определить, является ли данный год високосным
a = int(input())
if a % 4 == 0 and a % 100 != 0 or a % 400 == 0 or a % 3000 == 0: 
      print ("Високосный")
else:
      print("Обычный")
