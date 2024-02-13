**Coding challenge**

This page consists a set of coding challenges for Full Stack developer at RakInsurance.

**Purpose**
Evaluate your coding abilities
Judge your technical experience
Understand the solution design

**Evaluation**

Coding standard and comments
Unit testing strategy
Overall solution design
Appropriate use of source control

**Instructions**

Use Spring Boot, MVC framework.
Share the completed code in public code repository hosted in Github along with the testing results.
Use any other third party library or package of your choice if needed.
Use 1 pull request per coding challenge for code merging.


**Challenge 1**
Create an application that allows the uploading of a file. Once the file is loaded, the application must validate and parse each line of file information (plaintext) and then upload the information to the database. The file structure is as follows:
x, y, z
x is the username id of a user. Its length is 10 characters. They are just numbers, and can have zeros on the left.
y the amount of coins associated with the user x. must accept only natural numbers.
z is the user name x.
The three fields are mandatory and can not be blank. If you find a wrong value when making the validation of each line, stop the process and if the database is modified, returning it to its initial state. Warn the user which line had an error.

**Challenge 2**

Lets assume we are an online marketing company. We got some new requirment to capture phone numbers of our customers every customer can have many phone numbers (1 customer : N phone numbers) and we need following 2 APIs from backend team:
Get all phone numbers
Get all phone numbers of a single customer

Create an UI to display the results in Angular/React with the customer search option 

**Bonus Points**

Implement pagination concept to display the results in UI.
Make web app responsive preferably with bootstrap framework.
Try to deploy your solution on free hosting provider.
