Welcome to my Manual Testing Course Project!

This project is designed to test the booking functionality of a website through automated tests using Selenium and JUnit. Let's take a quick tour of the key components:

BookingLoginTest:
This test logs into the website, performs a login action, and validates the successful login by checking a welcome message.
It utilizes utility methods from UtilityMethods for interacting with the web page.

UtilityMethods:
Contains utility methods to interact with web elements using JavaScriptExecutor, such as selecting text in the welcome message.

BookingProcessTestFailed:
This test simulates a failed booking process by selecting a room, providing dates, and attempting to book a holiday.
It handles different scenarios like successful booking or unavailability and prints corresponding messages.

BookingProcessTestSuccess:
Similar to the failed booking test, this test simulates a successful booking process by selecting a room, providing dates, and booking a holiday.
It verifies the success message and prints appropriate output.

BaseTestClass:
This class sets up and tears down the WebDriver for the tests.
It maximizes the browser window for better visibility during test execution.

Quick Overview:
The tests navigate to a specific website, interact with login functionality, and simulate booking processes.
The use of utility methods enhances code reusability and maintains a cleaner structure.
Tests include explicit waits (Thread.sleep()) for better synchronization, but consider using WebDriverWait for more robust handling.
The project uses ChromeDriver, and there's commented-out code for EdgeDriver if needed.

Feel free to explore the tests based on your specific requirements. Happy testing!👌
