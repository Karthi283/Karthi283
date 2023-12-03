balance=0
print("ATM")
print("""
1)  balance
2)  withdraw
3)  deposit
4)  quit
   """)
option=int(input("enter option:"))
if option==1:
 print("balance",balance)
if option==2:
 print("balance",balance)
withdraw=float(input("enter withdraw amount"))
if withdraw>0:
 forewardbalance=(balance-withdraw)
 print("Foreward Balance", forewardbalance)
elif Withdraw>balance:
    print("No funs in account")
else:
 print("None withdraw made")
if Option==3:
 print("Balance", balance)
Deposit=float(input("Enter deposit amount:"))
if Deposit>0:
 forewardbalance=(balance+Deposit) 
 print("Forewardbalance", forewardbalance)
else:
 print("None deposit made")
if Option==4:
 exit() 
