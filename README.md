# Problem Title: TripCraft — Itinerary Scheduling and Budget Control Planner

**Problem ID:** CP-050

## Team Members

1. **Name:** Harshini D| USN: 1AT24CS072
2. **Name:** Keerthana| USN: 1AT24CS091

**Track:** Java   
**Domain:** Travel, Transport and Logistics

---

## Problem Description

Group trips can become difficult to manage when activities overlap, expenses exceed the planned budget, and members are unsure about individual contributions.

TripCraft is a Java-based console application that helps users organize group trips, schedule daily activities, detect timing conflicts, track expenses, and manage the overall travel budget.

---

## How to Run the Program

### Prerequisites

- Java Development Kit (JDK) installed.
- A terminal or command prompt.
- VS Code or any Java-supported IDE.

### Steps

1. Clone or download this repository.

2. Open the project folder in your terminal.

3. Compile the Java program:

```bash
javac TripCraft.java
```

4. Execute the program:

```bash
java TripCraft
```

5. Follow the menu displayed in the terminal to create a trip and manage its activities.

---

## Project Structure

```text
capstone-CP-050-Harshini-Keerthana/
│
├── TripCraft.java
├── TripCraft_Itinerary.txt
├── README.md
└── .gitignore
```

**File Description:**

- `TripCraft.java` – Contains the complete Java implementation, including trip creation, activity scheduling, budget calculations, and file handling.
- `TripCraft_Itinerary.txt` – Stores the exported trip itinerary.
- `README.md` – Contains project information and execution instructions.
- `.gitignore` – Specifies files Git should ignore.

---

## Features Implemented

1. **Create a Trip**
   - Enter trip name, destination, start date, and end date.
   - Add multiple travellers.
   - Set the total trip budget.

2. **Add Activities**
   - Add activities for specific dates.
   - Enter activity name, start time, end time, and planned cost.
   - Select the member responsible for payment.

3. **Detect Overlapping Activities**
   - Check activity timings on the same day.
   - Prevent scheduling conflicts.
   - Allow activities that are scheduled back-to-back.

4. **Track Planned and Actual Expenses**
   - Record actual spending for activities.
   - Compare estimated costs with actual expenses.
   - Display the remaining trip budget.
   - Notify users when spending exceeds the budget.

5. **Day-wise Itinerary and Per-person Cost**
   - Display activities date-wise and time-wise.
   - Calculate total planned and actual expenses.
   - Calculate equal per-person contributions.
   - Display individual member payment balances.

### Stretch Features 

- Save the complete itinerary to a text file for sharing.
- Suggest activities based on predefined destination recommendations.
- Identify planned activities that can be removed to bring the estimated cost within budget.

---

## Java Concepts Used

- **Object-Oriented Programming:** Classes, objects, constructors, and encapsulation of trip-related data.
- **ArrayList:** Dynamically stores trip members and activities.
- **LinkedHashMap:** Stores predefined destination-based activity suggestions.
- **LocalDate and LocalTime:** Handle trip dates and activity timings.
- **DateTimeFormatter:** Formats date and time values.
- **Comparator:** Sorts activities by date and start time.
- **Exception Handling:** Handles invalid inputs and file-related errors.
- **File Handling:** Uses FileWriter and PrintWriter to save itineraries.
- **Method Overloading:** Supports displaying the itinerary in the console and writing it to a file.

---

## Sample Run

### Input:

```text
========== TRIPCRAFT ==========
1. Create New Trip
2. Add Activity
3. Update Actual Spending
4. View Day-wise Itinerary
5. Budget Analysis and Suggestions
6. Save Itinerary to File
7. Exit

Enter your choice: 1

Enter Trip Name: Goa Vacation
Select Destination: Goa
Enter Start Date: 20-12-2026
Enter End Date: 22-12-2026
Enter Total Budget: 20000

Enter Number of Members: 4

Enter Member Names:
1. Harshini
2. Keerthana
3. Ali
4. Varsha

Trip created successfully!
```

### Output:

```text
========== TRIPCRAFT ==========
Trip Name   : Goa Vacation
Destination : Goa
Members     : 4
Total Budget: Rs. 20000

Trip created successfully!

Enter your choice: 2

Enter Activity Name: Water Sports
Enter Activity Date: 20-12-2026
Start Time: 10:00 AM
End Time: 12:00 PM
Planned Cost: 1200

Select Member Responsible for Payment: Harshini

Activity added successfully!
```

### Overlapping Activity Detection

```text
Enter Activity Name: Beach Visit
Enter Activity Date: 20-12-2026
Start Time: 11:00 AM
End Time: 01:00 PM

Activity overlaps with an existing activity!

Existing Activity: Water Sports
Please enter a different time.
```

### Budget Summary

```text
========== BUDGET SUMMARY ==========

Total Budget       : Rs. 20000
Planned Expenses   : Rs. 2600
Actual Expenses    : Rs. 2900
Remaining Budget   : Rs. 17100

Per Person Actual Cost: Rs. 725

====================================
```

*Note: The above is an illustrative sample demonstration. Actual console formatting and values depend on the information entered during execution.*

---

## Expected Outcome

TripCraft provides a simple and organized way to manage group travel plans through a Java console application.

It helps users:
- Avoid scheduling conflicts.
- Monitor travel expenses.
- Stay within the planned budget.
- Understand individual contributions.
- Maintain and share a structured travel itinerary.

---
