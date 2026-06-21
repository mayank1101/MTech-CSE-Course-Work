# Advanced Data Structures and Algorithms (CSL006P1M)

M.Tech, Semester 1

This directory archives lecture material, assignment sheets, and C++ solutions for the Advanced Data Structures and Algorithms course.

## Topics

- Asymptotic analysis and algorithmic foundations
- Divide-and-conquer techniques
- Greedy algorithm design
- Dynamic programming
- Approximation algorithms
- NP theory

## Contents

- [`Assignments/`](Assignments/) contains the tutorial and lab problem statements.
- [`PPT/`](PPT/) contains course slides and handouts, organized by topic where applicable.
- [`lab/`](lab/) contains 32 C++ programs across four assignment groups, including sorting, connected components, polynomial multiplication, greedy methods, coin change, knapsack, and highway-billboard problems.

## Running the programs

The lab files are independent programs rather than one buildable application. Compile the program you want to inspect with a C++11-or-newer compiler, for example:

```bash
g++ -std=c++11 "lab/Assignment 1/merge.cpp" -o merge
./merge
```

Some programs expect input files, console input, or assumptions documented only in the corresponding assignment PDF. Review the source and problem statement before running it. Compiled binaries are intentionally ignored by the repository-level `.gitignore`.

## Notes

- File names and directory names retain their original assignment naming.
- The course directory does not include a separate license. Refer to the repository root README for licensing and third-party-material notes.
