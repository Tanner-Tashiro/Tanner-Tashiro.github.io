---
layout: project
type: project
image: img/DatabaseLogo.png
title: "Database Project"
date: 2025
published: true
labels:
  - C
  - C++
summary: "In the Fall 2025 semester, I made a database in C and C++ for my ICS 212 class."
---

This project implements a C++ command-line Bank Database Application that allows users to manage customer records through an interactive text-based interface. The program serves as the user interface layer and works in conjunction with a linked list class to store, retrieve, and alter bank account records. The application supports adding new records, printing all existing records, finding records by account number, and deleting records by account number. 

This project was completed individually, and I was able to gain practical experience in structured software development using C++. The project reinforced the importance of validating user input, handling a variety of cases, and using debugging tools effectively. Additionally, I developed better habits for writing clear documentation and organizing code in a way that supports future extensions and debugging, which are essential skills in collaborative software development environments.
  
Here is some code that illustrates how we read user input and execute actions:

```cpp
while (running)
    {
        std::cout << "\nPlease choose an option:\n"
                  << "  add:      Add a new record\n"
                  << "  printall: Print all records\n"
                  << "  find:     Find record(s) by account number\n"
                  << "  delete:   Delete record(s) by account number\n"
                  << "  quit:     Quit the program\n";

        std::getline(std::cin, input);

        if (matchCommand(input, "add"))
        {
            int accountno = getAccountNum();
            std::string name;
            std::string address;

            std::cout << "Enter name: ";
            std::getline(std::cin, name);

            std::cout << "Enter address (end with '!'):\n";
            getAddress(address);

            mylist.addRecord(accountno, name.c_str(), address.c_str());
        }
        else if (matchCommand(input, "printall"))
        {
            std::cout << mylist;
        }
```
