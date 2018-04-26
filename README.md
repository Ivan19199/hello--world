# hello--world
Програма з використанням умовного оператора
#include <iostream>

using namespace std;

int main()
{
    int Ivan_score, Roman_score;

    cout << "vvedit znachennia Ivan_score:";
    cin >> Ivan_score;

    cout << "vvedit znachennia Roman_score:";
    cin >> Roman_score;

    if (Ivan_score > Roman_score)
    {

        if (Ivan_score >=4 )
        cout << "sho za..." << endl;
        else
        cout << "bachite, a vi kazali scho vihraete" << endl;
    }

      else

       cout << "shoe Ivasu, ya tobi scho kazav" << endl;



   /* if (Ivan_score < Roman_score)
    {
        cout << "ya tobi scho Ivasu kazav" << endl;
    }

    if (Ivan_score == Roman_score)
    {
        cout << "nehai bude nichiya" << endl;*/



    cout << "faina bula gra" << endl;

    return 0;
}
