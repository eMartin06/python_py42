def számolas(x):
    return 2*x-3

lista=[]

for i in range(-3,5):
    szám=számolas(i)
    if szám not in lista and szám >=0:
        lista.append(szám)
        
print("Az értékkészlet elemei: ", lista)