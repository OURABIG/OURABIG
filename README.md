#include <iostream>
#include <cmath>

using namespace std;

int main()
{
    
    string color, pluralnoun, celebrity;

    cout << "enter color: ";
    getline(cin, color);

    cout << "enter plural noun: ";
    getline(cin, pluralnoun);

    cout << "enter celebrity: ";
    getline(cin, celebrity);

    cout << "roses are " << color << endl;
    cout << pluralnoun <<" are blue" << endl;
    cout << "I love "<< celebrity << endl;

     return 0;
}

