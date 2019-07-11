# PlandayWebSite
Example for automation test in Planday website:

The Selenium script performs the following actions and checks, before outputting the results in a readable format:
 
 
1) Navigate to https://www.planday.com/signup/signup/#/personal
 
2) Populate all three text fields with invalid data and click submit without checking the check box

3) Verify that submission was unsuccessful, and check that appropriate error messages have appeared beneath each field

4) Now populate the fields with the following data

    Email - “martinjosephbakewell+” +(RandomNumber) + ”@gmail.com” - make sure the email address that was used is output with the results

    Name - "Test Please Ignore"

    Password - Generate a random 8 character password, make sure it is included with the results output

5) Check the checkbox and submit the form

6) Verify that the page arrived at is https://www.planday.com/signup/signup/#/company
 
7) Verify that the fields Company Name, Industry, Number of Employees and Phone Number are present
 
8) Attempt to verify the presence of a field "Made Up Field" that does not exist, in order to force the test to fail. Capture this failure in the results, coupled with a meaningful error message explaining the issue.
 
9) Verify that the "Number of Employees" drop down field contains the following options

1 - 9 
10 - 20
21 - 40
41 - 100
+101

