#include <iostream>
using namespace std;

int main() {
    int num;
    
    // Ask the user to input a number
    cout << "Enter a number: ";
    cin >> num;
    
    // Check if the number is even or odd using modulus operator
    if (num % 2 == 0) {
        // If the remainder when divided by 2 is 0, it's an even number
        cout << "Even number." << endl;
    } else {
        // If the remainder when divided by 2 is not 0, it's an odd number
        cout << "ODD number," << endl;
    }

    return 0;
}
