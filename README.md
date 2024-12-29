# sorting-character-arrays
#include <iostream>
#include<algorithm>
using namespace std;

int main() {
    char arr[]={'k','l','j','u'};
    int length =sizeof (arr)/sizeof(arr[0]);
     cout<<"array before sorting"<<endl;
     for(int i=0;i<length;i++){
         cout<<arr[i]<<endl;
     }
     cout<<endl;
     sort(arr,arr+length);
      cout<<"array after sorting in asceeding order"<<endl;
      for( int i=0;i<length; i++){
          cout<<arr[i]<<endl;
      }
      cout<<endl;
      sort(arr,arr+length,greater<char>());
      cout<<"array in decdeing order"<<endl;
      for(int i=0;i<length;i++){
          cout<<arr[i]<<endl;
          
      }
      cout<<endl;
                     
    return 0;
}
