# Online Bus Booking

Question: Build an automation framework and automate the tasks listed below.

Web Application: BusOnlineTicket Booking.

Want to learn:

Hit the above-mentioned URL.
Select Cameron Highlands as the source and Kuala Lumpur as the destination.
Select the date as the 20th of next month.
Search for a bus.
Select seats for the bus with the least adult cost (Do not use the sort button) and select a maximum of 6 seats, or all seats if fewer than 6 are available in the layout.
Click on Proceed and enter personal details.
Click on Proceed to payment (Do not choose any payment type), assert for the alert pop-up, and print the alert message.
Points: I’m using a "Hybrid Framework," which is a combination of "Data Driven + POM structure." In this framework, I use a Maven Project to provide a structure that follows user standards, like:

src/main/java
src/main/resources
src/test/java
src/test/resources
src folder
target folder
The pom.xml file handles the dependencies; once added, Maven will automatically download them.

Additionally, I use TestNG for script execution with the help of its annotations.

The framework uses Selenium as the automation tool. I also maintain utility classes and a base class for structure and reusability.

