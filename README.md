# tttt
thise is test
#include <iostream>
#include <iomanip>
#include "windows.h"
#include <cmath> 

using namespace std;

int main()
{
	SetConsoleCP(1251);
	SetConsoleOutputCP(1251);
	double x, a, b, c, f;
	cout << "Введіть x: ";
	cin >> x;
	cout << "Введіть a: ";
	cin >> a;
	cout << "Введіть b: ";
	cin >> b;
	cout << "Введіть c: ";
	cin >> c;
	if (x < a && x == a) f = fabs(6 * a * a - 8 * b) + x * x;
	if (a < x && x < b) f = (sqrt(1 + x)) / a - 3 * b;
	if (x > b && x == b) f = sqrt(1.9 + pow(x, 1.7) + pow(tan(x), 5));
	cout << setprecision(2) << "F=" << f << endl;
