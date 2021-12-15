import sys
nTemp = int(input())
ans = 0
nums = input().split()
for number in nums:
    if int(number) < 0:
     ans += 1 
     print (ans)
