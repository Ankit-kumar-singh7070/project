#include <bits/stdc++.h>
using namespace std;

void towerOfHanoi(int n,char source,char auxiliary, char destination) 
{
  if (n == 0) return;
  if(n==1){
    cout<<source<<  " "<<destination<<endl;
  }
    towerOfHanoi(n - 1, source,destination,auxiliary);
    cout << source <<" "<< destination << endl;
    towerOfHanoi(n - 1,auxiliary,source,destination);
}
    
int main()
{
    int n;
    cin>>n;
 main
    towerOfHanoi(n, '1', '2', '3','4','5');

    towerOfHanoi(n, '1', '2', '3','4','5');
 main
    return 0;
}
