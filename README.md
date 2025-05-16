#include<iostream>
using namespace std;
int main()
{
cout<<"---------------SIMPLE CALCULATOR---------------"<<endl;
char ch;
cout<<"Press c for calculate or any other keys to quit:";
cin>>ch;
while(ch=='c')
{
int first_num,second_num;
cout<<"Enter first number:";
cin>>first_num;
cout<<"Enter second number:";
cin>>second_num;
string operation;
cout<<"Enter Operator:";
cin>>operation;
if(operation=="+")
{
cout<<first_num+second_num<<endl;
}
else if(operation=="-"){
cout<<first_num-second_num<<endl;
}
else if(operation=="*"){
cout<<first_num * second_num<<endl;
}
else if(operation=="/"){
cout<<float (first_num)/float( second_num)<<endl;
}
cout<<"Press c for calculator again or any other keys to quit:";
cin>>ch;
}
return 0;
}
