# swapping-of-two-numbers-using-call-by-reference strategies.

#include<iostream>
using namespace std;
void swap (int &number1, int &number2) 
{
        int temp;
        temp=number1;
        number1=number2;
        number2=temp;
}
int main()
{
        int a=30,b=50;
        cout<<"\n Before swapping"<<"\n A = "<<a<<"\n B = "<<b<<endl;
        swap(a,b);
        cout<<"\n After swapping"<<"\n A = "<<a<<"\n B = "<<b<<endl;
        return 0;
}
