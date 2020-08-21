/*relational operators*/

#include <iostream>
using namespace std;

int main()
{
    int a,b;
    bool c;
    cout <<"enter the value of a and b :"<<endl;
    cin >>a;
    cin >>b;
    c=a<b;
    cout<<"a less than b :"<<c<<endl;
    c=a>b;
    cout<<"a is greater than b :"<<c<<endl;
    c=(a==b);
    cout<<"a is equal to b :"<<c<<endl;
    c=(a<=b);
    cout<<"a is less than or equal to b :"<<c<<endl;
    c=(a>=b);
    cout<<"a is greater than or equal to b :"<<c<<endl;
    c=(a!=b);
    cout<<"a is not equal to b :"<<c<<endl;
    return 0;
}

![output](relational_op.png)
