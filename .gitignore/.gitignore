f1=open('m1.mp4','rb')
f2=open('v1.bin','wb')
f3=open('v2.bin','wb')
c=0
#count the no. of bytes
for i in f1:
 c=c+1

 

print('c=',c)

a=c//2
b=a+1

f1.close()

f1=open('m1.mp4','rb')
a1=0
for i in f1:
 f2.write(i)
 a1=a1+1
 if a1==a :break

b1=b
for i in f1:
 f3.write(i)
 b1=b1+1
 if b1==c-1 :break


print('tell',f1.tell())
f1.close()
f2.close()
f3.close()
print("\nsplit finished")

f1=open('v1.bin','rb')
f2=open('v2.bin','rb')
f3=open('finaldone.mp4','wb')
c=0
for i in f1:
 f3.write(i)
 c=c+1

for i in f2:
 f3.write(i)
 c=c+1

print("finished c=",c)

