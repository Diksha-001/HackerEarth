#include<bits/stdc++.h>
using namespace std;
#define ll long long
 
 
#define nl '\n'
#define all(a) a.begin(),a.end()
#define all(a) a.begin(),a.end()
void solve()
{
    int n,k;    
	  cin>>n>>k;
    int ar[n];
    for(int i=0;i<n;i++){         cin>>ar[i];
    }     sort(ar,ar+n);     int l =0,r=n-1;
    while(l<r){
        int sum = ar[l] + ar[r];
        if(sum == k){
            cout<<"YES"<<nl;
            return;
        }         
    else if(sum<k){
            l++;
        }         
    else{
            r--;
        }
    }
    cout<<"NO"<<nl;
    return ;
}
int main()
{
    solve();
}
