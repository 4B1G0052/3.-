設定座標x為變數x,座標y為變數y
圓形直徑為200
半徑為100
100^2=10000(a)
(x*x)+(y*y)=輸入的圓範圍(b)
若a>=b則在圓內(insild)
反之在圓外(outsild)

#include<iostream>
using namespace std;
int main()
{
    int x, y;
    while (cin >> x >> y) {
        int a = 10000;
        double b = (x * x) + (y * y);
        if (a >= b) {
            cout << "inside\n";
        }\n
        else {
            cout << "outside\n";
        }

    }
    return 0;
}
