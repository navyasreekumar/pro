list1=[11,22,33,44,55]
el=[]
ol=[]
for i in list1:
    if i%2==0:
        el.append(i)
    else:
        ol.append(i)
print(el,'\n',ol)
