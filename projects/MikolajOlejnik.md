---
layout: project
studentName: "Mikolaj Olejnik"
supervisorName: "Dr Ludovic Magerand"
projectTitle: "Semi-automated tests for a network programming coursework"
projectImage: "automated_tests.jpg"

---


<hr>

## Project Description
This overarching goal of this project was to produce a series of semi-automated tests to aid the marking process of the IRC programming assignment within AC31008 - Networks.

The project contains several bot clients on two separate systems. Each client sends various commands to student's implementations of an IRC bot and IRC server. The clients then check whether they received the expected response, and output whether the student failed the given test.

The tests are based on a test framework created by the student. The framework was designed to be scalable and intuitive in the event that the marking criteria for the assignment is changed.

**The project provides the user with:**

- Series of tests for student bot implementations
- Series of tests for student server implementations
- A simple framework for expanding the current set of tests
- Synchronisation of clients on different nodes on a network


