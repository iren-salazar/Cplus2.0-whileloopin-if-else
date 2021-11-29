# Cplus2.0-whileloopin-if-else
if less than or equal to 5 " too far" else its " a bit more"

#include <iostream>
using namespace std;

int main()
{
    int x=0;
    while (x<=10)
    {    
        if (x<=5)
        { 
            cout << "Too far!" << endl;
        }
        else
        {
            cout << "A bit more!" << endl;
        }
        x++;
    cout << x;
    }       
}
  /*output:
  
  Too far!
  1 Too far!
  2 Too far!
  3 Too far!
  4 Too far!
  5 Too far!
  6 A bit more!
  7 A bit more!
  8 A bit more!
  9 A bit more!
  10 A bit more!
  */
