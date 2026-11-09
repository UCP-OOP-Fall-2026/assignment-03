# Advanced Object-Oriented Programming
## CSCP2023 – Object-Oriented Programming

This repository is the starter project for the **Smart University Resource Management System** assignment.

## What you need to do

Create the six required classes yourself:

- `Person`
- `Student`
- `Course`
- `Assignment`
- `Submission`
- `ResourceManager`

For every class, create a header file (`.h`) for declarations and a corresponding implementation file (`.cpp`) for member-function definitions.

## Required project structure

Your completed repository should follow this structure:

```text
Advanced-OOP-Assignment/
├── main.cpp
├── Person.h
├── Person.cpp
├── Student.h
├── Student.cpp
├── Course.h
├── Course.cpp
├── Assignment.h
├── Assignment.cpp
├── Submission.h
├── Submission.cpp
├── ResourceManager.h
├── ResourceManager.cpp
├── docs/
│   └── UML.png
└── README.md
```

## Important instructions

1. Create all six classes yourself; class header and implementation templates are not provided.
2. Follow the requirements and marks distribution in the assignment brief.
3. Keep class declarations in header files and define member functions in their respective `.cpp` files.
4. Use header guards or `#pragma once`.
5. Do not use global variables.
6. Do not make private data members public.
7. Do not use `using namespace std;` in header files.
8. Implement and demonstrate the required memory-management behavior.
9. Add your UML class diagram inside the `docs/` directory.
10. Complete `main.cpp` to demonstrate the interaction between the classes and all required concepts.
11. Test that the complete project compiles and runs before submitting.

## Compilation

From the project root, compile all implementation files together. For example, with g++:

```bash
g++ -std=c++11 -Wall -Wextra -pedantic main.cpp Person.cpp Student.cpp Course.cpp Assignment.cpp Submission.cpp ResourceManager.cpp -o university_system
```

Run on Linux/macOS:

```bash
./university_system
```

On Windows (MinGW):

```bash
university_system.exe
```

Update the compile command if you add any additional `.cpp` files.

## Submission checklist

- [ ] All required `.h` and `.cpp` files are present.
- [ ] UML diagram is saved in `docs/`.
- [ ] `README.md` explains the project, class responsibilities, operator overloads, memory management, and build/run steps.
- [ ] All required tasks are demonstrated in `main.cpp`.
- [ ] The project compiles and runs successfully.
- [ ] Changes are committed and pushed to your assigned GitHub Classroom repository.

**Academic integrity:** Submit your own implementation. You should be able to explain your design decisions and demonstrate your code during evaluation.
