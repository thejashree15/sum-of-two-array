# sum-of-two-array
#include <iostream>
using namespace std;

int main() {
    int n;
    cout << "Enter size of arrays: ";
    cin >> n;

    int arr1[n], arr2[n], sum[n];

    cout << "Enter elements of first array: ";
    for(int i = 0; i < n; i++) {
        cin >> arr1[i];
    }

    cout << "Enter elements of second array: ";
    for(int i = 0; i < n; i++) {
        cin >> arr2[i];
    }

    // Sum through index
    for(int i = 0; i < n; i++) {
        sum[i] = arr1[i] + arr2[i];
    }

    cout << "Resultant sum array: ";
    for(int i = 0; i < n; i++) {
        cout << sum[i] << " ";
    }
    return 0;
}
