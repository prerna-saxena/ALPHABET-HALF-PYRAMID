# ALPHABET-HALF-PYRAMID




#include <iostream>
using namespace std;

int main() {
    char input, alp='A';
    cin>>input;
    input=toupper(input);
    for(int i=1; i<=(input-'A'+1); i++){
        for(int j=1; j<=i; j++){
            cout<<alp<< " ";
        }
        ++alp;
        cout<<endl;
    }
    return 0;
}
            
        
