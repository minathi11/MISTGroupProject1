Team 6 MIST 4610 Group Project 1
Team Name:
39217 Group 6

Team Members:
David Tran
Nick Kalenik NickKalenik
Minathi Mekala
Ngoc Nguyen ngocpn1
Anthony Ramage
CJ Tumlin
Problem Description:
Our team has been tasked to model and create a relational database for the operations of "Athens Tennis Haven", a tennis club in Athens, Georgia. The club has a complex network of relationships between club members, tennis courts, club staff, tennis equipment, etc. We plan to accurately model these relationships and populate realistic data for each entity and their attributes. With this data, we will create a series of queries to extract meaningful information from the database to make important busines decisions for Athens Tennis Haven.

Data Model:
Data Model Explanation: Our model works to ensure a good flow to serve the 3 main entities: courts, members, and employees. A club can have multiple courts that can be utilized in different ways. Maintenance Employees can log the times they will service the courts, members can schedule Sessions for the Lessons with their coaches, and they can make reservations on their own. This is all connected to the Courts table that allows the Tennis Club to see all activities going on within those courts. Employees belong to different Departments. Maintenance Employees are connected to the courts through Services, and Coaches can make Lessons, which are connected to the courts through Session, with their students. The club has many members. They are Billed individually and can be in Teams. Members can also rent out equipment needed to use at the courts. They can make reservations with the courts to practice either by themselves or for their teams, and they can join a Session to get Lessons with their coach.

Screenshot 2023-11-03 at 3 37 34 PM

Data Dictionary:
Screenshot 2023-11-03 at 3 46 30 PM

Queries:
ComplexityTable

Query 1 lists the amount of “Fulfilled” maintenance requests by court number. It descends from the highest number of “Fulfilled” comments to lowest.
Query1SS

Query 1 allows managers to see the courts that require the most amount of maintenance. These courts may see the most use from players or patrons watching games, so it may show management that these courts need significant upgrades to lessen the amount of needed maintenance requests.

Query 2 lists all tennis club members and the amount of times they have made a court reservation.
Query2SS

Query 2 allows managers to see how active all members are with court reservations. Management could thank the very active members to keep them happy, and they could contact non active members to improve club participation.

Query 3 lists each team, their number of members and the total amount of equipment that each team (through its members) has rented
Query3SS

Query 3 allows managers to see how active each team is, their number of members and how much each team in total is making rentals of equipment. This would be important for management to know if they wanted to check on their team's activities.

Query 4 identifies the type of equipment that has been rented most by members, in descending order.
Query4SS

Query 4 allows management to study the usage rates of the equipment they offer for rent. They could decide to purchase more units of equipment that is in high demand, and they could choose to delay further purchases of equipment that rarely gets rented out.

Query 5 produces a list of members that have made at least three court reservations but have not taken any lessons. This query also lists out the members contact information, and orders the members by last name alphabetically.
Query5SS

Query 5 allows management to determine the beginner-level members who like to play a lot of tennis, but may have not taken any lessons yet. This is a business opportunity for the club, as they can reach out to these members to offer them lessons.

Query 6 produces the contact information for members who have not rented out any equipment.
Query6SS

Query 6 allows management to see members that potentially are not active within the club. Contacting them with a reminder that the club offers equipment rentals may encourage them to rent and thus play more tennis.

Query 7 produces the average salary for assistant coaches.
Query7SS

Query 7 allows management to compare the average salary of their assistant coaches to other clubs in the area. If they are experiencing high coach turnover, they are most likely underpaying them. If they are experiencing high operating costs, they may need to decrease their average pay.

Query 8 lists out the names of members and what equipment they have rented within the last 5 months
Query8SS

Query 8 can be used by management to track rentals within the last 5 months. This can be important for management to track trends and see what equipment has been rented recently.

Query 9 lists all of the employees, their departments, and their salaries in descending order by department. Query9SS Query 9 can be used by management to quickly see what all employees in each department are currently being paid. This can help management when trying to decide how much a new-hire should make or whether an employee is due for a raise.

Query 10 will display how many rackets the club has.

Query10SS

Query 10 can be helpful to management by providing a quick glance at the quantity of rackets in stock. If they need to purchase more or less, this query can assist them.

Database Information:
Name of database: ns_F2339217Group6
