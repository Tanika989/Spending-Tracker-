Spending Tracker App

1. Introduction

The Spending Tracker App is an Android mobile application developed using Kotlin and Android Studio. The purpose of the application is to help users monitor their daily spending, manage their budgets, and improve their financial habits.

The application allows users to view their weekly spending information and calculate the remaining budget for each day and the entire week.

2. Objectives

The main objectives of the application are to:

* Help users monitor their daily expenses.
* Allow users to compare daily budgets with actual spending.
* Calculate the remaining budget for each day.
* Calculate the total remaining budget for the week.
* Encourage responsible spending and better financial management.

3. Application Features

Splash Screen

* Displays the Spending Log logo.
* Displays the application name.
* Automatically navigates to the main screen after three seconds.

Main Screen

Provides three navigation buttons:

* View All Spending
* Calculate Remaining Budget
* Exit App

View All Spending Screen

Displays the seven days of the week with their corresponding:

* Date
* Daily budget
* Daily amount spent
* Spending comments

A Back button allows users to return to the main screen.

Calculate Remaining Budget Screen

* Calculates the remaining budget for each day.
* Displays the remaining amount for every day.
* Calculates and displays the total remaining budget for the week.
* Provides a Back button to return to the main screen.

4. Data Storage

The application uses four parallel arrays, each containing seven elements representing the seven days of the week.

The arrays are:

1. Dates – Stores the dates or days of the week.
2. Daily Budget – Stores the allocated budget for each day.
3. Daily Spent – Stores the amount spent each day.
4. Comments – Stores descriptions of daily expenses.

Each array uses the same index to keep the information for a particular day together.

5. Calculations

The application calculates the remaining daily budget using the following formula:

Remaining Budget = Daily Budget - Daily Spent

The total weekly remaining budget is calculated by adding the remaining amounts for all seven days.

6. Programming Concepts Used

The application demonstrates the following programming concepts:

* Kotlin programming language.
* Variables and data types.
* Parallel arrays.
* Functions and methods.
* For loops.
* Conditional navigation.
* Mathematical calculations.
* Jetpack Compose user interface.
* Screen navigation.
* Coroutines and time delays.

7. Technologies Used

* Android Studio
* Kotlin
* Jetpack Compose
* Android SDK

8. Sample Weekly Data

Day	Budget	Spent
Monday	R500	R350
Tuesday	R400	R250
Wednesday	R600	R400
Thursday	R500	R300
Friday	R700	R550
Saturday	R800	R600
Sunday	R400	R200

Total Weekly Budget: R3,900

Total Weekly Spending: R2,650

Total Remaining Budget: R1,250

9. Conclusion

The Spending Tracker App provides a simple and user-friendly way to monitor daily and weekly expenses. By using parallel arrays, functions, loops, and calculations, the application demonstrates important Kotlin programming concepts while helping users understand and manage their spending.

The application encourages better budgeting habits and supports improved financial awareness.
