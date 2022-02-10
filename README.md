# 10-02-2022-ass-1
#Write python program to generate student result whether pass or fail.
studentno=int(input('enter student no:'))
studentname=input('enter student name:')
studentgroup=input('enter student group:')
s1=int(input('English marks:'))
s2=int(input('Telugu marks:'))
s3=int(input('Online business:'))
s4=int(input('Analytical skills:'))
s5=int(input('Environment studies:'))
s6=int(input('Accounting:'))
s7=int(input('java:'))
s8=int(input('Operating system:'))
if(s1>=35 and s2>=35 and s3>=27 and s4>=27 and s5>=27 and s6>=35 and s7>=35 and s8>=35):
    print('pass')
else:
    print('fail')
    
output:
enter student no:23
enter student name:jahnavi
enter student group:bca
English marks:65
Telugu marks:72
Online business:45
Analytical skills:47
Environment studies:45
Accounting:67
java:70
Operating system:68
pass
