# Introduction

In this homework assignment, you will practice working with a simple C++ class.

# Tasks
1. Complete the class named `tank_car` in car.h. Since the member functions are simple, implement them directly inside the class definition. The `tank_car` class has the following members:
* "Private" member variables:
  * double-typed `radius`
  * double-typed `length`
  * string-typed `name`
* "Public" member functions:
  * constructor without parameters: initializes the member variables `radius`, `length`, and `name` to 1.2, 34.5, and "No name", respectively.
  * constructor with parameters: initializes the member variables `radius`, `length`, and `name` using its parameters `r`, `l`, and, `n`, respectively.
  * setter named `write_radius`: updates the `radius` member variable with the value passed in parameter `r`.
  * setter named `write_length`: updates the `length` member variable with the value passed in parameter `l`.
  * setter named `write_name`: updates the `name` member variable with the value passed in parameter `n`.
  * getter named `read_radius`: returns the current value of the `radius` member variable.
  * getter named `read_length`: returns the current value of the `length` member variable.
  * getter named `read_name`: returns the current value of the `name` member variable.
  * member function `volume`: calculates and returns the volume of the tank car using the formula $\pi \times radius^2 \times length$. This member function does not take any parameters. Use the math constant `M_PI`, which is defined in the `cmath` standard library, for $\pi$.
2. Complete the `main` function in main.cpp. See the comments marked with TODO for detailed instructions on specific sub-tasks. You may need to call the implemented member functions.

# Compile and Test

1. Type the following commands on Terminal.

```
g++ -o main *.cpp
```
```
./main
```

2. Input
* This homework assignment does not require any input. Below are the expected outputs:

```
== Information on No name ==
  radius: 1.2
  length: 34.5
  volume: 156.074
== Information on TC1 ==
  radius: 3.4
  length: 10.1
  volume: 366.8
== Information on TC2 ==
  radius: 5.6
  length: 2.1
  volume: 206.893
```

# Submit

Please upload your `main.cpp` and `car.h` files (two files) to `myCourses > Assignments > HW6`. Do not submit *.docx, *.pdf, *.txt, or *.zip file.
