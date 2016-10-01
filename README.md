Hello

My name is Aleksander and Im from poland. Im a self learning programmer who knows c++/c# and Im eager to learn different programming languages. I dont have troubles with using english but if its possible I would prefer to work in polish.

- [x] I know `Swift`/`Objective-C`

Im most comfortable with c++, but learning different language makes no problem for me. 

Source code:

#include <iostream>
#include <iomanip>

using namespace std;

int main()
{
long double a=1,b=1,c=1,x,y;
cout<<setprecision(10000);
cout<<"Type amount of fibonacci numers you want to display : ";
cin>>x;
cout<<endl<<"Type how many you want to skip : ";
cin>>y;
cout<<" "<<endl;
    for(int i=0;i<x;i++)
    {
    b=a;
    a=c;
    c=a+b;

        if(i>=y)
        {
        cout<<c<<endl;
        }
    }

    if(x<=y)
    {
    cout<<endl<<endl<<"0";
    }

    else if(x==y+1)
    {
    cout<<endl<<endl<<c;
    }

    else if(x==y+2)
    {
    cout<<endl<<endl<<c+a;
    }

    else
    {
    cout<<endl<<endl<<a+b+c;
    }

return 0;
}


