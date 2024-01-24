[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/tYncE4AO)
# quiz1_class_and_objects

## Instructions:
Please fill in the blank
```cplus
/*
* Name:
*/

// Question: Create a C++ class representing a car with attributes like model, year, and color. Include a method to display car details.
// Answer: --------------------------------------- here

#include <iostream>
#include <string>

class Car {
private:
    std::string model;
    std::int year;
    std::string color;
public:
    //car year getter and setter
   int get_year (){
        return year;
    }
    void set_year (std::int newyear){
        year = newyear;
    }
    //car model getter and setter
    string get_model (){
        return model;
    }
    void set_model (std::string newmodel){
        model = newmodel; 
    }
    //car color getter and setter
    string get_color (){
        return color;
    }
    void set_color (std::string newcolor){
        color = newcolor;
    }

    //display car details
    void displayDetails() {
        std::cout << "Model: " << model << ", Year: " << year << ", Color: " << color << std::endl;
    }
};

int main() {
    Car myCar;

    myCar.displayDetails();

    return 0;
}

```
