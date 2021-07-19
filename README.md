# Cplusplus
/*Write a C++ Program to C++ Program to Add Two Numbers. Here’s simple Program to Add Two Numbers in C++ Programming Language.

In this program, user is asked to enter two integers. Then, the sum of those two integers is stored in a variable and displayed on the screen.
*/
#include <iostream>

using namespace std;

int main()
{
    int n,m,sum;
    cout<<"Enter a 1st integer = ";
    cin>>n;
    cout<<"Enter a 2nd integer = ";
    cin>>m;
    sum=n+m;
    cout<<"Sum of two numbers ["<<"n"<<"+"<<"m]="<<sum;
    return 0;
}
