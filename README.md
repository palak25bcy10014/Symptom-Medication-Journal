# Symptom & Medication Journal

## 📌**Overview**

The Symptom & Medication Journal helps users track their health by recording medications taken or symptoms experienced.
It allows users to log occurrences (e.g., taking a medication or feeling a specific symptom) and view a summary of their health events. 
It is a console-based, beginner-friendly program.

## 📌**Features**
* **Add Item:** Register a new medication or symptom (Name + Category/Dosage).
* **Log Occurrence:** Record an event for a specific item (increments the event count).
* **View Summary:** View a list of all tracked health items with their total occurrence counts.
* **Simple Interface:** Easy-to-use menu-driven navigation.

## 📌**Technology**
* **Language:** Python 3.7
* **Input/Output:** Standard Console I/O
* **Data Structure:** List of Dictionaries
 
## 📌**Testing Instructions**

### Test Case 1: Add a health(medication or symptoms)

Select Option 1.
Enter Name: Fever.
Enter category (Medication/Symptom): symptom.
Expected Result: Item added to journal!

### Test Case 2: Log an occurrance

Select Option 2.
Choose the number corresponding to Fever.
Expected Result: System confirms "Logged event for Fever!".

### Test Case 3: Invalid Input (Non-Functional Testing)

Select Option 2.
Enter a non-numeric value or value which is not valid (e.g., "abc").
Expected Result: System catches the error and prints "Invalid input" without crashing.

## 📌**How to Run**
1. Ensure you have Python installed.
2. Open your terminal or command prompt.
3. Run the command:
   ```bash
   python Symptom_& _Medication_Journal.py
   
## 📌**Project Structure**
Symptom & Medication Journal/
* ├── Symptom_& _Medication_Journal.py
* ├── README.md
* ├── Report.pdf
* ├── /screenshots
* └── /recordings
   
## 📌**Screenshots**
### 1.Menu Drive

<img width="840" height="197" alt="image" src="https://github.com/user-attachments/assets/ef3293d4-9793-4337-a12f-ae16a5aff6c7" />

### 2.Entering choice as 1

<img width="810" height="294" alt="image" src="https://github.com/user-attachments/assets/1a816b0b-1216-4c81-96c7-677df413d700" />

### 3.Entering choice as 2 and checking for error by entering wrong input

<img width="1130" height="380" alt="image" src="https://github.com/user-attachments/assets/c4565a72-172b-4cab-9228-4ccf4bc946c9" />

### 4.Entering choice as 2 and checking result by entering correct input

<img width="1093" height="367" alt="image" src="https://github.com/user-attachments/assets/f5dd67ae-ba01-407e-8f90-bb11a92227f8" />

### 5.Entering choice as 3 and checking for the summary

<img width="817" height="283" alt="image" src="https://github.com/user-attachments/assets/e56f58ff-39e9-464d-b705-19662c80bf91" />
