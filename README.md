# Assignment-
Assignment 
#include <iostream>
using namespace std;

int main() {
    int arr[10]; // Declare a static array of size 10

    // Populate array with user input
    cout << "Enter 10 integers:" << endl;
    for(int i = 0; i < 10; i++) {
        cin >> arr[i];
    }

    // Print all values
    cout << "The values in the array are: ";
    for(int i = 0; i < 10; i++) {
        cout << arr[i] << " ";
    }
    cout << endl;

    return 0;
}
