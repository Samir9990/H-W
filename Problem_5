#include <iostream>
using namespace std;

int main () {
    int days;
    int year;
    int month;

    year = days / 365 ;
    if (year == 0) {
        month = days / 30;
        days = days - (year * 365 + month * 30);
    } else {
        month = (days - 365) / 30;
        days = days - (year * 365 + month * 30);
    }


    cout << year << endl;
    cout << month << endl;
    cout << days << endl;

    return 0;
}
