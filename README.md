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
```

## 🔄 Data Flow
Input: Reads structured player data from input.txt.

Processing: Stores data in an internal memory array of CricketTeam structures.

Analysis: Provides 9 analytical functions accessed via a menu-driven interface (Options A-I).

Output: Displays results in the console and exports filtered player lists to Player_info.txt.

## 🌟 Key Features
Player Search: Quickly find player details by name.

Statistical Analysis: * Identify the Top Scorer.

Find the most experienced player (Matches played).

Filter players by type (e.g., All-rounders).

MVP Calculation: Features a custom weighted formula to determine the Most Valuable Player.

Data Export: Save processed results directly to a text file for external use.

## 🚀 How to Use
Ensure your player data is formatted correctly in input.txt.

Compile the source code:
