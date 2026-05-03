##### Finding the maximum/minimum of a set of numbers.



\#include <iostream>

using namespace std;



int main() {

&#x20;   int count;

* &#x20;   double num, maxNum, minNum;



&#x20;   cout << "How many numbers do you want to enter? ";

&#x20;   cin >> count;



&#x20;   if (count <= 0) {

&#x20;       cout << "Invalid count!" << endl;

&#x20;       return 1;

&#x20;   }



&#x20;   cout << "Enter number 1: ";

&#x20;   cin >> num;

&#x20;   maxNum = minNum = num; // تهيئة الحد الأقصى والأدنى بأول رقم



&#x20;   for (int i = 2; i <= count; i++) {

&#x20;       cout << "Enter number " << i << ": ";

&#x20;       cin >> num;

&#x20;       if (num > maxNum) maxNum = num;

&#x20;       if (num < minNum) minNum = num;

&#x20;   }



&#x20;   cout << "Maximum number: " << maxNum << endl;

&#x20;   cout << "Minimum number: " << minNum << endl;



&#x20;   return 0;

}

