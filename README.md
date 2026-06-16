FLIGHT BOOKING AUTOMATION FRAMEWORK (GITHUB PROJECT STRUCTURE)

Repository Name:
selenium-flight-booking-automation

Project Structure:
FlightBookingAutomation/
│
├── pom.xml
├── README.md
│
├── src
│   ├── main
│   │   └── java
│   │       └── pages
│   │           ├── HomePage.java
│   │           ├── FlightSelectionPage.java
│   │           └── PurchasePage.java
│   │
│   └── test
│       └── java
│           └── tests
│               └── FlightBookingTest.java
│
├── utilities
│   ├── DriverFactory.java
│   └── ConfigReader.java
│
├── test-output
│   └── ExtentReports
│
├── screenshots
│   └── booking_success.png
│
└── .gitignore


README.md

# Flight Booking Automation Framework

Project Overview:
This project automates the complete flight booking workflow on:
https://blazedemo.com/

Tech Stack:
• Java
• Selenium WebDriver
• TestNG
• Maven
• WebDriverManager

Features:
✔ Select departure city
✔ Select destination city
✔ Search flights
✔ Verify flight list
✔ Choose a flight
✔ Enter passenger details
✔ Enter payment details
✔ Complete booking
✔ Verify confirmation message

Design Pattern:
• Page Object Model (POM)

Run Project:
1. Clone repository
   git clone <repo-url>

2. Import into Eclipse

3. Maven Update Project

4. Run TestNG Test

Author:
Abhilash


GitHub Topics:
selenium
java
testng
automation-testing
webdriver
maven
page-object-model
flight-booking
blazedemo
sdet


Recommended Commit History:
1. Initial Maven Setup
2. Added Driver Factory
3. Created Home Page Object
4. Created Flight Selection Page
5. Created Purchase Page
6. Implemented Flight Booking Test
7. Added Assertions and Validations
8. Updated README
9. Final Project Submission


Skills Demonstrated:
• Java
• Selenium WebDriver
• TestNG
• Maven
• Page Object Model (POM)
• Explicit Waits
• Assertions
• Automation Framework Design
• Git
• GitHub

Project Flow:
1. Open BlazeDemo Website
2. Select Departure City
3. Select Destination City
4. Click Find Flights
5. Verify Available Flights List
6. Select One Flight
7. Verify Purchase Flight Page
8. Enter Passenger Details
9. Enter Payment Details
10. Click Purchase Flight
11. Verify Successful Booking Confirmation

Expected Output:
"Thank you for your purchase today!"
Flight booking completed successfully.
