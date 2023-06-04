#include <bits/stdc++.h> 
void sort012(int *arr, int n)
{
   int l= 0, h= n-1, mid=0;
   while(mid<=h){
      if(arr[mid]==0){
         swap(arr[l], arr[mid]);
         l++;
         mid++;
      }
      else if(arr[mid]==2){
         swap(arr[h], arr[mid]);
         h--;
      }
      else{
         mid++;
      }
   }
}
