#include <iostream>
using namespace std;
 
int main() {
    int A, B, C;
    cin >> A >> B >> C;
 
    int min = A;
    if (B < min) {
        min= B;
    }
    if (C < min) {
        min = C;
    }
 
    int max = A;
    if (B > max) {
        max = B;
    }
    if (C > max) {
        max = C;
    }
 
    int mid = A + B + C - min - max;
 
    cout << min <<endl;
    cout << mid <<endl;
    cout << max << endl;
    cout<<endl; 
    cout << A <<endl; 
    cout<< B <<endl; 
    cout<<C << endl;
 
    return 0;
    
}
