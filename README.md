#include <iostream>
using namespace std;

class Employee
{
    public:
            int empid;
            int salary;
            
   Employee setInfo()
    {
        Employee e;
        e.empid=1001;
        e.salary=500;
        return e;
    }
};




int main()
{
   Employee e1;
   e1 = e1.setInfo();
   cout<<e1.empid<<endl;
   cout<<e1.salary<<endl;
    return 0;
}
