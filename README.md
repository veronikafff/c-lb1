#include <iostream>   
#include <cmath>     
using namespace std;

int main() {
   
    double a, b, y;
    cout << " a: ";
    cin >> a;
    cout << " b: ";
    cin >> b;
    double numerator = 0.1 * log(pow(exp(1), 3)); // 0.1 * ln(e^3)
    double denominator = pow(sin((a / b) * M_PI), 2) + pow(cos((a / b) * M_PI), 2);
    y = cbrt(numerator / denominator);
    cout << "result: " << y << endl;

    return 0;
}


