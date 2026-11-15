# ✈️ TripCraft – Itinerary Scheduling and Budget Control Planner

**Project Code:** CP-050  
**Domain:** Travel, Transport and Logistics  
**Project Type:** Console-Based Application

## 📌 Project Overview

TripCraft is a Java-based travel itinerary and budget management application designed to make group trip planning easier and more organized.

When planning group trips, managing expenses and scheduling activities can become difficult. Activities may overlap, expenses may exceed the planned budget, and splitting costs among members can be confusing.

TripCraft helps users create trips, schedule activities, detect time clashes, track actual spending, monitor budgets, and calculate individual contributions.

## 🎯 Objectives

- Simplify group trip planning.
- Avoid overlapping activities.
- Track planned and actual expenses.
- Help users stay within their trip budget.
- Calculate per-person costs and member contributions.
- Generate and save a day-wise travel itinerary.

## ⭐ Features

### 1. Create a New Trip
- Enter trip name and destination.
- Set trip start and end dates.
- Enter the total trip budget.
- Add the names of trip members.
- Prevent duplicate member names.

### 2. Add Activities
- Add activities for individual trip dates.
- Specify activity name, date, start time, and end time.
- Enter the planned cost.
- Select the member responsible for payment.
- Validate activity dates and timings.

### 3. Overlapping Activity Detection
- Automatically checks for overlapping activities on the same day.
- Displays the conflicting activity details.
- Prompts the user to enter a different schedule.

### 4. Actual Spending Tracker
- Record actual expenses for each activity.
- Update spending whenever additional expenses occur.
- Compare actual spending with the total trip budget.
- Display the remaining budget.

### 5. Day-wise Itinerary
- Display all activities date-wise.
- Show activity timings, planned costs, actual costs, and payment details.
- Automatically arrange activities by date and starting time.
- Display days without scheduled activities.

### 6. Budget Analysis and Suggestions
- Compare planned expenses with the total budget.
- Identify whether the trip is within or over budget.
- Allow users to remove activities that have no recorded spending.
- Suggest additional activities based on the selected destination and remaining budget.

### 7. Per-Person Cost Calculation
- Calculate the equal expense share for each member.
- Display the amount paid by each member.
- Calculate the net balance.
- Identify members who have paid extra or owe money to the group.

### 8. Save Itinerary to a Text File
- Save the complete trip itinerary.
- Include trip information, activities, and expense summaries.
- Store member-wise contribution details.
- Generate a file named `TripCraft_Itinerary.txt`.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Java | Core application development |
| Java Collections | Store trip members and activities |
| ArrayList | Manage activities and members |
| LocalDate | Handle trip and activity dates |
| LocalTime | Manage activity timings |
| DateTimeFormatter | Format time input and output |
| File Handling | Save itinerary as a text file |
| Scanner | Accept user input |

## 📂 Project Structure

```text

capstone-CP-050-Harshini-Keerthana/
│
├── .gitignore
├── README.md
├── TripCraft.java
└── TripCraft_Itinerary.txt

```

*Note: The `.class` files are generated after compilation, and the itinerary text file is generated when the user selects the save option.*

## ⚙️ Installation and Execution

### Prerequisites
- Java Development Kit (JDK 8 or above)
- Visual Studio Code or any Java-supported IDE
- Terminal or Command Prompt

### Step 1: Clone the Repository

```bash
git clone <https://github.com/Harshini-projex/capstone-CP-050-Harshini-Keerthana>
```

### Step 2: Open the Project Folder

```bash
cd capstone-CP-050-Harshini-Keerthana
```

### Step 3: Compile the Java Program

```bash
javac TripCraft.java
```

### Step 4: Run the Application

```bash
java TripCraft
```

## 🖥️ Application Menu

The application provides the following menu options:

```text
================================================================================
                              TRIPCRAFT
                    ITINERARY & BUDGET PLANNER
================================================================================
  1. Create New Trip
  2. Add Activity
  3. Update Actual Spending
  4. View Day-wise Itinerary
  5. Budget Analysis & Suggestions
  6. Save Itinerary to File
  7. Exit
================================================================================
```

Users can select an option by entering its corresponding number.

## 📊 Sample Supported Destinations

TripCraft currently provides predefined activity suggestions for four destinations.

| Destination | Sample Activities |
|---|---|
| Goa | Dolphin Boat Ride, Fort Aguada Visit, Water Sports |
| Manali | Solang Valley Adventure, Hadimba Temple, River Rafting |
| Jaipur | Amber Fort, City Palace, Food Walk |
| Mysuru | Mysore Palace, Chamundi Hills, Brindavan Gardens |

## 📁 Output

After selecting the save option, the application generates:

`TripCraft_Itinerary.txt`

The file contains:
- Trip details and destination.
- Travel dates and member information.
- Day-wise activity schedule.
- Planned and actual expenses.
- Remaining budget.
- Per-person contribution and net balance.

## 👥 Contributors

**Project Team:**
- Harshini D
- Keerthana K L

## 🏁 Conclusion

TripCraft provides a simple and practical solution for managing group travel schedules and expenses. By combining itinerary scheduling, overlapping activity detection, budget monitoring, and expense tracking, it helps users plan trips more efficiently and avoid common planning difficulties.

**Plan Smart. Travel Better!** ✈️
