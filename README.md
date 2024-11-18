#include <iostream>
using namespace std;

int main() {
    int num1, num2, sum;
    int* p1, * p2, * ps;
    cout << "Enter first number: ";
    cin >> num1;
    cout << "Enter second number: ";
    cin >> num2;
    p1 = &num1;
    p2 = &num2;
    ps = &sum;
    *ps = *p1 + *p2;
    cout << *p1 << "+" << *p2 << "=" << *ps;

    return 0;
}
