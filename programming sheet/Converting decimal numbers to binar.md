##### Converting decimal numbers to binary numbers :



\#include <iostream>

using namespace std;



int main() {

&#x20;   int n, bin\[32], i = 0;

&#x20;   cin >> n;



&#x20;   if (n == 0) {

&#x20;       cout << 0;

&#x20;       return 0;

&#x20;   }



&#x20;   while (n > 0) {

&#x20;       bin\[i] = n % 2;  

&#x20;       n /= 2;

&#x20;       i++;

&#x20;   }



&#x20;   for (int j = i - 1; j >= 0; j--) {

&#x20;       cout << bin\[j];

&#x20;   }



&#x20;   return 0;

}

