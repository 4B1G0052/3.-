設定座標x為變數x,座標y為變數y\n
圓形直徑為200\n
半徑為100\n
100^2=10000(a)\n
(x*x)+(y*y)=輸入的圓範圍(b)\n
若a>=b則在圓內(insild)\n
反之在圓外(outsild)\n

#include<iostream>\n
using namespace std;\n
int main()\n
{\n
    int x, y;\n
    while (cin >> x >> y) {\n
        int a = 10000;
        double b = (x * x) + (y * y);\n
        if (a >= b) {\n
            cout << "inside\n";\n
        }\n
        else {\n
            cout << "outside\n";\n
        }\n

    }\n
    return 0;\n
}\n
