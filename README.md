# Online Voting System – Python Mini Project

##  Project Overview
This project is an **Online Voting System** developed using **Core Python**.  
It is a menu-driven program that allows voters to log in using a voter ID, view candidates, cast a vote, and view voting results.

---

##  Core Concept Used: **Dictionary in Python**

### 🔹 What is a Dictionary?
A dictionary in Python is a data structure that stores data in the form of **key–value pairs**.  
Each key is unique and is used to access its corresponding value.

---

### 🔹 Why Dictionary is Used in This Project?
In this project, the dictionary is used to:
- Store candidate details
- Maintain vote counts
- Update votes efficiently
- Organize data in a structured way

---

### 🔹 Dictionary Implementation in the Project


candidates = {
    1: {"name": "Alice", "votes": 0},
    2: {"name": "Bob", "votes": 0},
    3: {"name": "Charlie", "votes": 0}
}
Explanation:

The key represents the candidate number.

The value stores the candidate name and number of votes.

🔹 How Voting Works Using Dictionary
candidates[choice]["votes"] += 1


When a voter selects a candidate, the program accesses the candidate using the key.

The vote count is increased by 1.
### 🔹 Advantages of Using Dictionary

* Easy data access

* Fast updates

* Clean and readable code

Suitable for real-world applications

### ▶ How to Run the Program

Install Python (version 3.x)

Run the file online_voting.py
###  Conclusion

The dictionary data structure plays a major role in this Online Voting System.
It helps manage candidates and vote counts effectively using Core Python.

## project video presentation.
https://drive.google.com/file/d/12CpK3PX9vhJsHeJiQiqQsqX17Y7dO_V5/view?usp=sharing
