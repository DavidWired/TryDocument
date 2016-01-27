# TryDocument
Can I add some code now?? I would like to find out right now.

# Cube root of a number.
x= int(raw_input('Enter a number please '))
ans=0
while ans**3 <abs(x):
    ans= ans+1
if ans**3!=abs(x):
    print 'Number is not a perfect cube.'
else:
    if x<0:
        ans=-ans
    print'cube root of', x, 'is' ,ans
