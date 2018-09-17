//# Problem-304
#include <iostream>

using namespace std;
int main()
{
    double x, y ,z;
    cin>>x>>y>>z;
    if (x > y && y > z)
        cout << z << " " << x << endl;
        else if (y > x && x > z)
        cout << z << " " << y << endl;
        else if (y > z && z > x)
        cout << x << " " << y << endl;
        else if (y > x && z > y)
        cout << x << " " << z << endl;
        else cout << y << " " << x << endl;
}
