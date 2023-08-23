# Dark-Light
# cook your dish here
for i in range (int(input())):
    n,k = map(int,input().split())
    if(k==0):
        if(n%4 != 0):
            print("OFF")
        else:
            print("ON")
    else:
        if(n%4!=0):
            print("AMBIGUOUS")
        else:
            print("ON")
