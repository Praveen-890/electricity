# electricity
# eb bill calculationdu  print("tamilnadu electricity board") print("welcome praveen") lmr=int(input("enter your last month reading:-")) cmr=int(input("enter your current month reading:-")) consumption=cmr-lmr print("your current consumption is:",consumption,"units") a=100 b=101 c=200 d=201 e=300 if consumption&lt;=a:     rpc=5 else:     if consumption>=b and consumption&lt;=c:         rpc=7     else:         if consumption>=d and consumption&lt;=e:             rpc=8         else:             rpc=10 print("your rpc is:",rpc) eb_bill=consumption*rpc print("your elecricity bill amount is rs.",eb_bill) print("-------thank you-------")
