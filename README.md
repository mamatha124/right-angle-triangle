# right-angle-triangle
a,b,c = map(int,input().split())
if a+b>c:
  if b+c>a:
    if a+c>b:
      print("Yes")
    else:
      print("No")
  else:
    print("No")
else:
  print("No")
