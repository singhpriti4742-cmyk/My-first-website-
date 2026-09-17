[ATM.py](https://github.com/user-attachments/files/32348885/ATM.py)
# Hi Priyanka singh
balance=5000
saved_pin="1234"
print("welcome to my ATM")
entered_pin=input("1234:")
if entered_pin==saved_pin:
	while true:
		print("n1:check balance:")
		print("2:withdrow")
		print("3:Exit")
		choice=input("choice your num(1/2/3):")
		if choice=="1":
			print(f"your current balance:{balance}")
		elif choice=="2":
			amount=int(input("kitne paise nikalne hai"))
			if amount<=balance:
				balance==balance-amount
				print(f"rs{amount}")
				print(f"rs{balance}")
			else:
				print("wrong amount!you have no enough money")

		elif choice=="3":
				print("thank you!have a good day")
				break

			else:
				print("wrong num!please choice1,2,or3")
else:
	print("wrong pin! plese try again")

		
