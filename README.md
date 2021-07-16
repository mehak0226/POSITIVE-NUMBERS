# POSITIVE-NUMBERS
lis=[]
x=int(input("how many elements in list"))
count=0
while(count<x):
    new=int(input("enter new element"))
    lis.append(new)
    count=count+1
print(lis)
for i in lis:
    if(i>=0):
        print("positive",i)
    else:
        continue
