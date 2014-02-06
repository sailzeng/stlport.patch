stlport.patch
=============

stlport patch,make stlport can compile in vc++ 2010,2012,2013.
Please copy cover stlport with this directory file.

1.Modify make file,configure.bat to support Microsoft Virsaul 
 C++ 2010,Virsaul C++ 2012,Virsaul C++ 2013 .

2.Modify stlport\stl\_cmath.h file,hypot function areadly 
support in VC++ 2013.

3.Modify stlport\stl\_cstdlib.h file,abs(long long) function 
areadly support in VC++ 2010.

