# ticket-servcie
#Assumptions
1.	There are no criteria specified for best available seat, so the program consider any available seat from left to right and top to bottom as best available. Therefore, adjacent seats are not guaranteed.
2.	Command line runner is being provided for testing purpose. However, it is assumed that the service would be invoked from frontend GUI.
3.      Seat hold expiry time is configured as 120 seconds.

#Test and Build
Execute test case:
1.	mvn clean test

Run the program:
1.	mvn clean install
2.	cd target
3.	java -jar ticket-service-0.0.1-SNAPSHOT.jar


