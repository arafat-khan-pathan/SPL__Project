# Cricket Player Statistics Management System

A C-based application that manages cricket player data through file I/O operations and provides statistical analysis capabilities via a menu-driven interface.

---

## 📖 System Overview
This project is designed to handle fixed datasets of cricket players. It operates by loading data from an external file into memory, allowing for fast batch analysis and reporting.

## 🏗 Core Data Structure
The system uses a structured approach to store player profiles:

```c
struct CricketTeam {  
    char name[50];     // Player Name
    int age;           // Age
    char type[20];     // Player Type (Batsman, Bowler, etc.)
    int totalmatch;    // Total Matches Played
    int totalrun;      // Total Runs Scored
    int hightrun;      // Highest Score
};
