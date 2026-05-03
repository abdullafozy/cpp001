##### Converting binary numbers to decimal numbers :



\#include <iostream>

using namespace std;

\#include <cmath>

int main() {

&#x20;   int n;

&#x20;   cin >> n;

&#x20;   int decimal = 0, power=0;

&#x20;   while (n > 0) {

&#x20;       decimal += (n % 10) \* pow(2,power) ;

&#x20;       n /= 10;

&#x20;       power++;

&#x20;   }

&#x20;   cout << decimal;



&#x20;   return 0;

}

