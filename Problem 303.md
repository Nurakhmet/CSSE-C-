#include <iostream>
#include <cmath> 
using namespace std;
int main() {
    double a, b, c, y, l, m, n;
    cin>>a>>b>>c;
    y = (b*b) - (4*a*c);
    if (y==0) {
        l = sqrt(y);
        m = (-b+l)/(2*a);
        n = (-b-l)/(2*a);
        cout<<m<<" "<<n<<endl;
    }
    else 
    cout<<"no solution"<<endl;
}
