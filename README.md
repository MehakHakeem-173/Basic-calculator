#include<iostream>
using namespace std;
int main(){
int m, n;
cout<<"enter the value of m: ";
cin>>m;
cout<<"enter the value of n: ";
cin>>n;
char op;
cout<<"enter the operator: ";
cin>>op;
if(op=="+") cout<<m+n<<endl;
if(op=="-") cout<<m-n<<endl;
if(op=="*") cout<<m*n<<endl;
if(op=="/") cout<<m/n<<endl;
}
