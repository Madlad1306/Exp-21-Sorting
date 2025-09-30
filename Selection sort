#include <iostream>
using namespace std;

void selection_sort(int arr[], int n) {
    for (int i = 0; i < n - 1; i++) {
        int min_index = i;
        for (int j = i + 1; j < n; j++) {
            if (arr[j] < arr[min_index])
                min_index = j;
        }
        swap(arr[i], arr[min_index]);
    }
}

int main() {
    int numbers[] = {64, 25, 12, 22, 11};
    int length = sizeof(numbers) / sizeof(numbers[0]);

    selection_sort(numbers, length);

    cout << "Sorted array: ";
    for (int i = 0; i < length; i++)
        cout << numbers[i] << " ";
    cout << endl;

    return 0;
}




//Expected Output :
Sorted array: 11 12 22 25 64


  
