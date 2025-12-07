#include <iostream>
using namespace std;

int main() {
    int N;
    cout << "Enter number of food items sold: ";
    cin >> N;

    int profit, totalProfit = 0;

    for (int i = 0; i < N; i++) {
        cout << "Enter profit for item " << i + 1 << ": ";
        cin >> profit;
        totalProfit += profit;
    }

    cout << "Total Profit: " << totalProfit << endl;

    if (totalProfit > 5000) {
        cout << "Great Day" << endl;
    }

    return 0;
}
