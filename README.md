# Seminar2
Your task is to design a program for a vehicle inspection (bilprovning) company. In the  current iteration we are implementing the functionality Inspect Vehicle, who’s require- ments specification follows below. Remember to also design the startup, that is, the  main method. You should not write any code, just design the program.
Requirements Specification for Inspect Vehicle

The scenarios below describe basic flow and alternative flows when inspecting a vehicle.

Basic Flow

1. Inspector specifies that a new inspection may be started.

2. Program displays next customer’s queue number on display outside garage and opens garage door.

3. Customer enters garage.

4. Inspector instructs program to close garage door.

5. Program closes garage door.

6. Inspector enters vehicle’s license number.

7. Program retrieves appropriate inspections for vehicle.

8. Program tells cost for inspection.

9. Customer enters credit card information.

10. Program sends payment authorization request to an external payment authorization system, and requests payment approval.

11. Program prints receipt.

12. Customer receives receipt.

13. Inspector specifies that payment is completed.

14. Program tells inspector what to inspect on customer’s vehicle.

15. Inspector performs the specified inspection.

16. Inspector enters result of the specified inspection. The result is either pass or fail.

17. Inspector repeats steps 14-16 until program indicates that all inspections are completed.

18. Program stores inspection results. These results include information about failed inspections that must be repeated when the vehicle is fixed.

19. Program prints inspection results.

20. Inspector informs customer about results and hands over the printout.

21. Customer leaves garage.

Alternative Flows

6a. Invalid license number.

1. There are no inspections for the specified license number.

2. Program informs inspector that license number is invalid.

3. Inspector enters new license number.

9-11a. Paying by cash.

1. Inspector registers amount payed by the customer.

2. Program prints receipt and tells how much change the customer shall have.

3. Program updates the amount of cash present.
