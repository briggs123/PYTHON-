# PYTHON-https://classroom.github.com/assignment-invitations/72dccb2e6b852a2093a5379c09c78a9f
https://code.cs50.io/
a="25/25"
if "+" in a:
    b=a.replace("+"," ")
elif "-" in a:
    b=a.replace("-"," ")
elif "*" in a:
    b=a.replace("*"," ")
elif "/" in a:
    b=a.replace("/"," ")
c=[]
fact=1
sub=0
div=0
for x in b.split():
    c.append(int(x))
if "+" in a:
    print(sum(c))
elif "-" in a:
    for x in range(len(c)-1):
         sub=sub+(c[x]-c[x+1])
    print(sub)
elif "*" in a:
    for x in c:
        fact=fact*x
    print(fact)
elif "/" in a:
    for x in range(len(c)-1):
        div=div+(c[x]/c[x+1])
    print(div)

