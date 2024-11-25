just try this basic codes of c++
// variable
# include <iostream>
using namespace std;
int main()
{
    int num1 = 23;
    int num2 =45;
    int result = num1 + num2;
    cout << result <<endl;
    return 0;
}
........
//even no.
#include <iostream>
using namespace std;

int main() 
{
    int number;

    cout << "Enter an integer: ";
    cin >> number;

    if (number % 2 == 0) {
        cout << number << " is even." << endl;
    } else {
        cout << number << " is odd." << endl;
    }

    return 0;
}
