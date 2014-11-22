Studentmark
===========
this is new file
this is added by amans
#include<iostream.h>
#include<conio.h>
void caInput();
void best();
void validate();
void main()
{
clrscr();
input();
cal();
getch();
}


void caInput()
{
int test,quiz,termpaper;
test=25;
quiz=20;
termpaper=25;
}


//finding best component

void best()
{
  if(test>quiz)
       {
          if(test>termpaper)
               {
                   cout<<"test has heighest marks";
                }  
           else
                 {  
                    cout<<"termpaper has heighest marks";
                }  
         }
    else
        {
         cout<<"quizz has heighest marks";
        }
int a=((test>quiz)?(test>termpaper):test):quiz);
int b=((termpaper>quiz)?(termpaper>testr):termpaper;quiz));
ict ca=a+b;
cout<<"total sum of two best components"<<ca;
}
// validation
void validate()
{
int totalmarks=60;
int obtainCaMarks=50;
 int grade;
if(obtainCaMarks>45)
{
cout<<"A grade";
}
else
{
cout<<"B grade";
}
}
