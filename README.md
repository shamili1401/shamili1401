import random
AR=[20,30,40,50,60,70]
FROM=random.randint(1,3)

TO=random.randint(2,4)

for k in range(FROM,TO+1):
    print(AR[k],end="#")

