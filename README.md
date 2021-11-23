# Input / Output Array
```
#include <iostream>
using namespace std;
int main()
{
    cout << "enter 5 number: \n";
    int values[5];
    for (int x = 0; x < 5; x++)
        cin >> values[x];
    cout << "you entered:" << endl;
    for (auto value : values)
        cout << value << endl;
}
```
# Array ART
```
#include <iostream>
using namespace std;
int main()
{
    string art[5][5] = {
        {"-","-","-","-","-"},
        {"-","o","w","o","-"},
        {"-","@","@","@","-"},
        {"-","^","^","^","-"},
        {"-","v","v","v","-"},
    };
    for (int x = 0; x < 5; x++) {
        for (int y = 0; y < 5; y++) {
            cout << art[x][y] << "";
        }
        cout << endl;
    }
}
```
# Bunny ARRAY
```
#include <iostream>
using namespace std;
int main()
{
    string art[5][5] = {
        {"/",")","_","/",")"},
        {"(","*","u","*",")"},
        {"(",">"," ","<",")"},
        {" ","U"," ","U"," "},
        {"^","^","^","^","^"},
    };
    for (int x = 0; x < 5; x++) {
        for (int y = 0; y < 5; y++) {
            cout << art[x][y] << "";
        }
        cout << endl;
    }
}
```
