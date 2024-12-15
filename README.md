# C-task-2
#include <iostream>
using namespace std;

int main() {
    
    double a, b;
    char operation;

    
    cout << "Enter the first number: ";
    cin >> a;

    
    cout << "Enter the second number: ";
    cin >> b;

   
    cout << "Enter an operation (+, -, *, /): ";
    cin >> operation;

    
    if (operation == '+') {
        cout << "Result: " << a + b << endl;
    } 
    else if (operation == '-') {
        cout << "Result: " << a - b << endl; 
    } 
    else if (operation == '*') {
        cout << "Result: " << a * b << endl;
    } 
    else if (operation == '/') {
        
        if (b!= 0) {
            cout << "Result: " <<a/ b << endl; 
        } 
        else {
            cout << "Error: Cannot divide by zero!" << endl;
        }
    } 
    else {
        cout << "Error: Invalid operation!" << endl; 
    }

    return 0;
}
