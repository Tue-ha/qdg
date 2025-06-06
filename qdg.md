#include <iostream>
using namespace std;

int main() {
    double x;
    cout<<"Nhập số km đi được: ";
    cin>> x;
    if (x=1) {
        double y=x*15000;
        cout<<"Tiền taxi: "<<y<<endl;
    }
    else if (x>1&&x<=15) {
        double y=15000+(x-1)*13500;
        cout<<"Tiền taxi: "<<y<<endl;
    }
    else {
        double y=x*11000;
        cout<<"Tiền taxi: "<<y<<endl;
    }

    return 0;
}
