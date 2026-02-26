#include <iostream>
using namespace std;

int main() {
    double loan, insurance, gas, oil, tires, maintenance;
    double monthlyTotal, annualTotal;

    // Ask the user for monthly costs
    cout << "Enter monthly loan payment: ";
    cin >> loan;

    cout << "Enter monthly insurance cost: ";
    cin >> insurance;

    cout << "Enter monthly gas cost: ";
    cin >> gas;

    cout << "Enter monthly oil cost: ";
    cin >> oil;

    cout << "Enter monthly tires cost: ";
    cin >> tires;

    cout << "Enter monthly maintenance cost: ";
    cin >> maintenance;

    // Calculate totals
    monthlyTotal = loan + insurance + gas + oil + tires + maintenance;
    annualTotal = monthlyTotal * 12;

    // Display results
    cout << "\nTotal monthly cost: $" << monthlyTotal << endl;
    cout << "Total annual cost: $" << annualTotal << endl;

    return 0;
}
