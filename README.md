i = 0
while i<10:
	number=int(input("Hello! Please enter amount to be taxed:"))
	print(round(number*1.07, 2))
	print("Thank you!")
	i+= 1
print("Thank you for using me!\nHit the enter key to exit")
input()
