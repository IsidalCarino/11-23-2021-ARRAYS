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
# 
