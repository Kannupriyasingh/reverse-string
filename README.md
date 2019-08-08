
#include <iostream>
#include<string.h>
#include<stack>
#include<cmath>

using namespace std;

int main()//reverse string
{
    char str[10] ="ABCDE";
    stack<char>s;
    int i;
    for(i=0;i < strlen(str);i++)
        s.push(str[i]);
    cout<<"reversed string:";
    while (!s.empty())
    {
        cout<<s.top();
        s.pop();
    }
    return 0;
}
