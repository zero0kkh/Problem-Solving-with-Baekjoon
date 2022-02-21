/*
#1000
a, b = map(int, input().split())
print(a+b)

#2558 : input과 map의 이해 feat 2588의 히스토리
a=int(input())
b=int(input())
print(a+b)

#10950 : for 문
a=int(input())
for i in range(a):
  x,y=map(int,input().split())
  print(x+y)

#10951 : 예외처리
while True:
  try:
    x,y=map(int,input().split())
    print(x+y)
  except: break

while True:
  try:
    x,y=map(int,input().split())
    print(x+y)
  except EOFError: break

#10952 : 종결조건
while True:
  try:
    x,y=map(int,input().split())
    if x==0 and y==0: break
    print(x+y)
  except: break

#10953 : split
a=int(input())
for i in range(a):
  x,y=map(int,input().split(','))
  print(x+y)

#11021 : print with string (+formatting)
a=int(input())
for i in range(a):
  x,y=map(int,input().split())
  print("Case #"+str(i+1)+": "+str(x+y))
  #print('Case #{0}: {1}' .format(i+1, x+y))

#11022
a=int(input())
for i in range(a):
  x,y=map(int,input().split())
  print("Case #"+str(i+1)+": "+str(x)+" + "+str(y)+" = "+str(x+y))

*/
