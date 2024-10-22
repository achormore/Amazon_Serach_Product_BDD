# Amazon_Serach_Product_BDD
Search the product on amzon and verify title.
* This automated UI test framework was created based on BDD.

* Using Page Object Model (POM) as a design pattern.

* To verify web-based application testing Selenium WebDriver was used.

-----------------------  

* To achieve this test framework, test cases in Amazon web page following this steps were created:

  1. Launch the Chrome browser.

  2. Navigate to the URL: "https://www.amazon.com/".
  
  3. Enter the product name "iphone" in the search bar.
  
  4. Click on the search button.
  
  5. Verify that the first result contains the text "Apple iPhone".

  6. Close the browser.
 
-----------------------  

* In order to automate these test cases, the following classes and files were created:

   1. Pom.xml file where required dependencies has been added which are copied from maven repository.

   2. Feature file  in gherkin language where to declare the scenearios and declare in a parameterized way the items criteria to perform the search.
  
  4. Base page java class where a single instance of the webdriver is created, and different methods to interact with the web elements, the other pages will inherit these functionalities.
  
  5. Step java class  where the methods to be reproduced by the gherkin scenarios are implemented.
  
  6. Page java class  where we will inherit the functionalities from the base page for interact with web elements.
  
------------------------
  
  ## Technologies used:

   - Language: JAVA

   - Libraries: Selenium-Cucumber 

* Enviroment Configuration:

  - Download and set JAVA environment variables (JAVA_HOME and PATH):JDK (23.0.1)

  - Download and installation IDE (Eclipse IDE)
