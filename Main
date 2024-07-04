#include <iostream>
#include <random>
#include <vector>
using namespace std;

int randRan;

vector <int> sort(randRan);


void random(int min, int max){
  
  for (int i = 0; i < randRan; i++){
    random_device rd;
    uniform_int_distribution<int> dist(min, max);
    sort[i] = dist(rd);
  }
  cout << "Unsorted: ";
  for(int h: sort){
    cout << h << " ";
  }
}





void bubbleS() {
  for (int i = 0; i < (randRan)-1; i++) {
    for (int j = 0; j < (randRan)-i-1; j++) {
      if (sort[j] > sort[j+1]){
        int temp = sort[j];
        sort[j] = sort[j+1];
        sort[j+1] = temp;
      }
      }
    }
  cout << endl << endl << "Sorted: ";
  for(int x: sort){
    cout << x << " ";
  }
  }

int main() { 
  int mini;
  int maxi;

  cout << endl << "Enter the minimum number: "; cin >> mini;
  cout << endl << "Enter the maximum number: "; cin >> maxi;
  cout << endl<< "Enter the amount of random numbers: "; cin >> randRan;
  sort.resize(randRan); 
  random(mini, maxi);
  bubbleS();
}
