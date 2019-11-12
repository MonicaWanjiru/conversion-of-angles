# conversion-of-angles
This is a simple program for maths to help in converting angles from radians to degrees
#Logic is that 180 degrees=pi radians
import math
try:
   a=input('ENTER ANGLE IN DEGREES'\n)
   b=float(a)
   r=a*(180/math.pi)
   print 'ANGLE IN RADIANS =',r
except:
   print('ENTER A VALID ANGLE!')
