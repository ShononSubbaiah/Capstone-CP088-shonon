# CP-088 AthleteIQ: Athlete Performance Tracking and Selection System

## Team

Suraj.T (1AT24CS225), Shonon (1AT24CS207)

Java Track  
Domain: Sports, Athlete Performance Tracking and Selection

## How to Run

1. Open the project folder in VS Code.
2. Open the terminal.
3. Make sure Java 17 or above is installed.
4. Compile and run the program:

```bash
java AthleteIQ.java
```

To load sample data and run the program:

```bash
java AthleteIQ.java --demo
```

## Features That Work

1. Register athletes with name, sport and age group.
2. Record and manage athlete performance results for different tests:
   - 100m Sprint
   - Long Jump
   - 1500m Run
   - Push-ups
3. Track individual athlete performance history based on test dates.
4. Generate improvement reports showing percentage improvement between the first and latest test.
5. Rank athletes within their respective age groups based on their latest performance.
6. Set and manage minimum performance standards for different age groups.
7. Generate athlete selection lists based on whether they meet all the required performance standards.
8. Identify athletes whose performance has declined in two consecutive tests.
9. Generate text-based progress charts to visualize performance history.
10. Display all registered athletes and their details.
11. Automatically save and load athlete records, test results and performance standards using a text file (`athleteiq.txt`).

## Sample Run

### Main Menu

```text
=== AthleteIQ ===
 1. Register athlete
 2. Record test result
 3. Improvement report
 4. Rank in age group
 5. Set minimum standard
 6. Selection list
 7. Flag declining athletes
 8. Progress chart
 9. Show athletes
 0. Exit
```
