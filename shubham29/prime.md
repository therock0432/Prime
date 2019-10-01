#include<iostream.h>
void main()
{int a,i,count=0;
cout<<"enter a no.";
cin>>a;
for(i=1;i<=a/2;i++)
{if(a%i==0)
count++;}
if(count>0)
cout<<"number is not prime";
else
cout<<"number is prime";
}



