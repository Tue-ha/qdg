#include <iostream>
using namespace std;

int main() {
    int a, b, c;
    cout<<"Nhập cạnh a: ";
    cin>> a;
    cout<<"Nhập cạnh b: ";
    cin>> b;
    cout<<"Nhập cạnh c: ";
    cin>> c;
    if (a*a+b*b==c*c||a*a+c*c==b*b||b*b+c*c==a*a) {
        cout<<"Tam giác đó là tam giác vuông. "<<endl;
    } else if (a==b==c) {
        cout<<"Tam giác đó là tam giác đều. "<<endl;
    } else if (a==b||a==c||b==c) {
        cout<<"Tam giác đó là tam giác cân. "<<endl;
    } else if (a+b>c||a+c>b||c+b>a) {
        cout<<"Tam giác trên là tam giác thường. "<<endl;
    }
    else {
        cout<<"Không hợp lệ. "<<endl;
    }
    

    return 0;
}
