# PYTHON-https://classroom.github.com/assignment-invitations/72dccb2e6b852a2093a5379c09c78a9f
https://code.cs50.io/
d1 = {"Andhra": "Amaravati", "Madhyapradesh" : "Bhopal", "Maharastra" : "Mumbai" }
b=[]
c=""
for x in d1:
    c=c+str(x)+"->"+str(d1[x])+" "
for x in c.split():
    b.append(x)
print(b)
    
