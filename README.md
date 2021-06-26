# array-
to enter and display array elements
#include <iostream>
 
 using namespace std;
int main() {
int n[5];
cout<<"Enter elements: 
for (int i = 0; i < 5; ++i) {
cin>>n[i];
}
cout<<"you entered:"<<n;
return 0;
}
