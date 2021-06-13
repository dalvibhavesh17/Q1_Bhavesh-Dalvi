from array import *
x=input()
arr1=array('i',[])
li1=list(map(str,x.split())
for i in li1:
  arr1.append(i)
for i in arr1:
  if i<str(0):
    print('Invalid Input')
else:
  for i in range(len(arr1)):
     if (i+1).len(arr1)-1:
       break
     if len(arr[i])>len(arr1[i+1]):
       temp=arr1[i]
       arr1[i]=arr1[i+1]
       arr1[i+1]=temp
  print(arr1[0])
