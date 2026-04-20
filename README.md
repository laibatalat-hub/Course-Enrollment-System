# Course Enrollment & Fee Management System (C++)

A robust C++ console application designed to streamline the course selection process for engineering students. This system manages departmental data, semester-specific course offerings, and automated fee generation.

# Features
- **Multi-Department Support:** Specialized modules for Electrical (EE), Chemical (CE), and Mechanical Engineering (ME).
- **Semester Logic:** Organizes courses from Semester 1 through Semester 8.
- **Dynamic Fee Calculation:** Automatically calculates total tuition fees based on the specific credit hours (CH) of selected courses (Rate: 3500 per Credit Hour).
- **User-Friendly Interface:** Uses formatted console output for a clear, interactive experience.

## 💻 Logic Overview
The program uses a modular approach with separate functions for each department and fee calculation logic:
- **Department Modules:** `EE()`, `CE()`, and `ME()` handle user input for specific engineering tracks.
- **Data Storage:** Uses arrays to store selected course IDs for processing.
- **Calculation Engine:** Functions like `EEFees1()` through `MEFees8()` parse selection arrays to determine total credit hours and costs.
![Program Output](output.png)
