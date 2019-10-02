list1=[11,22,33,44,55]
el=[]
ol=[]
for i in list1:
    if i%2==0:
        el.append(i)
    else:
        ol.append(i)
print(el,'\n',ol)
#
#
duplicate=[2,4,10,20,5,2,20,4]
d=[]
i=0
f=0
while i<7:
    j=0
    while j<len(d):
        if duplicate[i]==d[j]:
            f=1
            break
        j=j+1
    if f==0:
        d.append(duplicate[i])
    i=i+1
print(d)
#
#
