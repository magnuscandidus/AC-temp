# AC-temp
# cook your dish here
h=int(input())
for i in range(h):
    a,b,c=map(int,input().split())
    if a<=b and b>=c:
        print("yes")
    else:
        print("no")
