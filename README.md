// penjumlahan dua bilangan bulat
#include <iostream>
using namespace std;

int calculateSum(int a, int b) {
  int sum = a + b;
  return sum;
}

int main() {
  int x = 5, y = 10;
  int result = calculateSum(x, y);
  cout << "The sum of " << x << " and " << y << " is " << result << endl;
  
  return 0;
}
