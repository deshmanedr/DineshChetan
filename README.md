

# This project is implemented to test the mentioned two test cases-

1. Success Credit Card Payment
2. Failed Credit Card Payment

# Prerequisite to run the test
1. Java 1.8 or higher
2. Maven

# Use the following commands to run the test
1. To run on Chrome -
mvn clean test -Dbrowser="chrome"
2. To run on Firefox-
mvn clean test -Dbrowser="firefox"

# Project Structure -
1. ReadExcelData.java is used to read the test data from the Excel File.
2. ReadPropertyFileData.java is used to read data from the properties file.
3. TestBase.java is a base class which contains driver configuration and generates extent report.
4. CardPayment.java contains the two test cases.
5. MidtransBasePage.java contains the required address of elements.

# Note -
Extent report shows exception java.lang.ClassNotFoundException: java.sql.Date when ran through command prompt. It has no impact on test result.
