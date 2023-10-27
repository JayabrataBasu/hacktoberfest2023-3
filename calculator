#include <iostream>
#include <cmath>
using namespace std;

int main() {
    double num1, num2, result;
    char op;

    cout << "Advanced Calculator" << endl;
    cout << "-------------------" << endl;
    cout << "Enter first number: ";
    cin >> num1;

    cout << "Select operation (+, -, *, /, %, ^, sqrt, sin, cos, tan): ";
    cin >> op;

    if (op != 'sqrt' && op != 'sin' && op != 'cos' && op != 'tan') {
        cout << "Enter second number: ";
        cin >> num2;
    }

    switch (op) {
        case '+':
            result = num1 + num2;
            break;
        case '-':
            result = num1 - num2;
            break;
        case '*':
            result = num1 * num2;
            break;
        case '/':
            if (num2 != 0)
                result = num1 / num2;
            else
                cout << "Error: Division by zero" << endl;
            break;
        case '%':
            result = fmod(num1, num2);
            break;
        case '^':
            result = pow(num1, num2);
            break;
        case 'sqrt':
            if (num1 >= 0)
                result = sqrt(num1);
            else
                cout << "Error: Square root of a negative number" << endl;
            break;
        case 'sin':
            result = sin(num1);
            break;
        case 'cos':
            result = cos(num1);
            break;
        case 'tan':
            result = tan(num1);
            break;
        default:
            cout << "Error: Invalid operation" << endl;
            return 1;
    }

    cout << "Result: " << result << endl;

    return 0;
}
