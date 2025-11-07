#include<iostream>
using namespace std;
#include<cmath>
int main()
{
	int x;
	cout << "please enter the volume of coffee in milliliters" << endl;
	cin >> x;
	if (x > 350)
	{
		cout << "Large size" << endl;
	}
	if (x > 200 && x < 350)
	{
		cout << "Medium size" << endl;
	}
	if (x < 200)
	{
		cout << "Small size" << endl;
	} return 0;

}
