# OOP-first-code
This is my first OOP program in my 2nd year i am trying my best for my logic building .


#include<iostream>
using namespace std;
class Student{
    public:
    string name;
    void display(){
        cout<<"Name:"<<name;
    }
};
int main(){
    Student s;
    s.name="Sneha";
    s.display();
    return 0;
}
