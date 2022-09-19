# parameter-constructor-
#include <iostream>
using namespace std;
class Cars
{
    string name;
    int price;
    public :
    Cars(string c_name, int c_price)
    {
         name = c_name;
         price = c_price;
    }
    
    void display()
    {
        cout<<"car name is "<<name<<endl;
        cout<<"car price is "<<price;
    }
};
int main()
{
    Cars c1("hyundai", 40000);
    c1.display();
}
