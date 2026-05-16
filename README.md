#include <iostream>
using namespace std;
int main(){
int n1,n2,n3;
cout<<"Enter first number:"<<endl;
cin >> n1;
cout <<"Enter second number"<<endl;
cin >>n2;
if(n1>n2){
n3=n1-n2;
}
else(n1<n2){
n3=n2-n1;
}
cout <<"Positive subtraction of two numbers are"<<n3<<endl;
return 0;
}
