# class_found
#include<bits/stdc++.h>

using namespace std;
class kausar
{
  public:
  int data;
  char name[100];
  float mark;
};

int main()
{
    kausar s;
    s.data=100;
    s.mark=12.35;
    char a[10]="kausar";
    strcpy(s.name,a);
    cout<<s.data<<" "<<s.mark<<" "<<s.name<<" "<<endl;

    return 0;
}
