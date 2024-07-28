-Install IntelliJ IDEA Community IDE Version 2018.3.6.
-Install OpenJDK 11 and complete the configuration.
-Install a Browser Driver(Chrome Driver).
-Setup a Selenium project with the name MyProjectsPageTest.

-Create a driver instance using WebDriver interface.
-Navigate to the url https://qamyprojects.ccbp.tech/
Perform the below tests,
Test the first project page
-Click the first project (<img> element) - use first-of-type & first-child pseudo-class.
-Print the title (<h1> element) of the project - use first-child pseudo-class.
-Print the description (<p> element) of the project - use nth-child pseudo-class.
-Click the "Back" button - use last-of-type pseudo-class.
Test the second project page
-Click the second project (<img> element) - use first-of-type & last-child pseudo-class.
-Find the Diwali items (<h1> element) - use nth-child pseudo-class.
-Find the Diwali prices (<p> element) - use last-child pseudo-class.
-Print all the items and their prices as below,
-Expected text: The price of <item> is: <price>.
-For example, "The price of Sparklers is: Rs 150".
-Click the "Back" button - use last-child pseudo-class.
Test the third project page
-Click the third project (<img> element) - use last-of-type & first-child pseudo-class.
-Print the title (<h1> element) of the project - use first-child pseudo-class.
-Print the description (<p> element) of the project - use nth-child pseudo-class.
-Click the "Back" button - use last-of-type pseudo-class.
Test the fourth project page
-Click the fourth project (<img> element) - use last-of-type & last-child pseudo-class.
-Print the category (<p> element) of the project - use first-child pseudo-class.
-Print the title (<h1> element) of the project - use nth-child pseudo-class.
-Print the description (<p> element) of the project - use nth-of-type pseudo-class.
Click the "Back" button - use last-of-type pseudo-class.
Close the browser window.

