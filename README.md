# lamprostechTestUdayBhola

list = [1,5,10]
target = 27
sum =0

# if any coin in list is equal to target then it required 1 coin only
if target in list:
    print("The minimun number of coins needed (1)")
    
    
# if the target is 0 then required is 0 coin
elif target == 0:
        print("The minimun number of coins needed (0)")

# if target is different then - 
elif target != sum :
    for i in list:
        sum = sum + i
        if sum == target:
            print("The minimun number of coins needed (2)")
    sum = sum + i
    print(sum)
