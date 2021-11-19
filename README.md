# Socre-counting
Score counting

#include <iostream>

using namespace std;

int main()
{

 int Chinese, English, Math,Science, Social;

 cout<<"please input the scores of 5 subjects:\n";
 
 cin>>Chinese>>English>>Math>>Science>>Social;

 cout<<"Total scores are:\n"<<Chinese+English+Math+Science+Social<<endl;

 cout<<"average socre is:"<<(float)(Chinese+English+Math+Science+Social)/5<<endl;  
  
  return 0;
 }
