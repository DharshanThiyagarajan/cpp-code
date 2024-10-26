# simple cpp codes # code to check is it leap year
#include<bits/stdc++.h> 
using namespace std;
class Solution{
public:
    int isLeap(int N){
        if ((N%4==0 && N%100!=0) || (N%400==0))
        {
            return 1;
        }
        else
        {
            return 0;
        }
    }
};

int main() 
{ 
    int t;
    cin>>t;
    while(t--)
    {
        int N;
        cin>>N;
        Solution ob;
        cout << ob.isLeap(N) << endl;
    
cout << "~" << "\n";
}
    return 0; 
}
