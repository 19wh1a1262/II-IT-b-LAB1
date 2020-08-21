/*logical operators*/

#include<iostream>

using namespace std;

int main(){
    int a = 20;
    int b= 21;
    cout<<(a > 10  && a != b)<<endl;
    cout<<(a > 30 || a == b)<<endl;
    cout<<!(a < b && a != b)<<endl;
    return 0;
}

