# guessing-number

#include<iostream>
using namespace std;
int main()
{
    int upper_bound=2;
    int lower_bound=10;
    int i;
    for(i=upper_bound;i<=lower_bound;i++)
    {
        std::cout<<i<<endl;
        int response;
        std::cin>>response;
        if(response==0)
        {
            std::cout<<"Guessed number is"<<i;
        }
    }
    return 0;
}
