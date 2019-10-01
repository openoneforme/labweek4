//labweek4

#include <iostream>
using namespace std;

void star()
{
    cout << "Name : Jasni Jazali Bin Mohd Zamri" << endl;
    cout << "Department : FTMK" << endl;
}

int main()
{
    star();
	float price = 9.90;
	int quantity;
	const int DISC = 10;
	float totalprice = 0;
	cout << "Enter quantity" << endl;
	cin >> quantity;
	totalprice = (price * quantity) * (100 - DISC) / 100.00;
    cout << "The total price is " << totalprice << endl;
    return 0;
}
