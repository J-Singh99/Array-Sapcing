#include <bits/stdc++.h>
using namespace std;

void spaceAdd(char*arr)
{
/*Build up this function.
  Make any sub-function calls if you need to.
  You have to make changes ONLY before int main().
  Taking input/giving output will be handled by me (a.k.a. Coolest Guy on Earth)
  Good luck,Human.*/
}

int main()
{
    char* arr = new char [100];

    cout<<"Enter the input. Put a $ to end input."<<endl;

    cin.getline(arr, 100, '$');              //Takes input. Ends if $ is entered.

    spaceAdd(arr);                           // Applies the Spacing function.

    for (int i = 0; arr[i]!='\0'; i++)       // Just a printing function.
    {
        cout<<arr[i];
    }

    return 0;
}
