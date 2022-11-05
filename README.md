nl=[]
for x in range(10, 150):
    if (x%17==0) and (x%5==0):
        nl.append(str(x))
print (','.join(nl))
