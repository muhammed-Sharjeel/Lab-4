# Lab-4
Programing fundamental lab task c++ source code, and practical work for BSCS students

TASK 1: Program to Calculate Weight

#include <iostream>
using namespace std;

int main()
{
    int units;
    double mass, weight;

    cout << "Enter mass: ";
    cin >> mass;

    cout << "Enter units: ";
    cin >> units;

    weight = mass * units;

    cout << "Weight = " << weight << endl;

    return 0;
}


TASK 2: Units Per Sales Representatives
#include <iostream>
using namespace std;
int main() {
    int units;
    double mass, weight;
    cout << "Enter mass: ";
    cin >> mass;
    cout << "Enter units: ";
    cin >> units;
    weight = mass * units;
    cout << "Weight = " << weight << endl;
    return 0;
}


TASK 4: Sum of Two Numbers
#include <iostream>
using namespace std;
int main() {
    int number1, number2, sum;
    cout << "Enter a number: ";
    cin >> number1;
    cout << "Enter another number: ";
    cin >> number2;
    sum = number1 + number2;
    cout << "The sum is " << sum << endl;
    return 0;
}

TASK 5: Divide Two Numbers
#include <iostream>
using namespace std;
int main() {
    int number1, number2;
    float quotient;
    cout << "Enter the first number: ";
    cin >> number1;
    cout << "Enter the second number: ";
    cin >> number2;
    if (number2 != 0) {
        quotient = (float)number1 / number2;
        cout << "The quotient is " << quotient << endl;
    } else {
        cout << "Cannot divide by zero." << endl;
    }
    return 0;
}

TASK 6: Sum and Average
#include <iostream>
using namespace std;
int main() {
    int number1, number2;
    float quotient;
    cout << "Enter the first number: ";
    cin >> number1;
    cout << "Enter the second number: ";
    cin >> number2;
    if (number2 != 0) {
        quotient = (float)number1 / number2;
        cout << "The quotient is " << quotient << endl;
    } else {
        cout << "Cannot divide by zero." << endl;
    }
    return 0;
}
