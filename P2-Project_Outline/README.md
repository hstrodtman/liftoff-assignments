# Project Outline
For this assignment, you will submit a high-level outline of your project. This can, and likely will, change over time. In particular, your mentor will provide direction and feedback to help sharpen your ideas. So don't worry if you feel unsure about some aspects of the outline or if you have to change some things later.

## Assignment Description
[Project Outline Assignment](https://education.launchcode.org/liftoff/modules/assignments/project-outline)

## Submission Instructions

### Overview
This project will be a web application that helps families prepare for children to be at home alone or with a babysitter. It will allow a parent to log in, add household information (family member info such as age, allergies, medications etc.), emergeny and babysitter contact information and allow the parent to create a printable with the household information, emergency contacts and other useful safety info. 

I decided to make this project because I was looking for a good way to prepare my daughters to stay home alone occasionally. With the recent school closures and social distancing requirements I feel this resource could be useful to many families that may need to leave their children unsupervised for a period of time. 

### Features

* **User Login:** Including authentication and password management to allows access to household specific features such as adding emergency contacts. 

* **Contacts Page:** Including fields for name, phone number, address, and ability to designate as emergency contact or babysitter. User will have CRUD capabilities for contacts. 

* **Family Members Page:** Including fields for name, DOB, allergies, medications, special instructions/needs, notes. Users will have  CRUD capabilities for family members. 

* **Printing Page:** Users will have access to a form to select information to include in a PDF. 

* **Basic Resources:**  Information such as state laws, safety information to go over with kids, advice for deciding if your child is ready to be home alone. Would be accessible without creating a log in. 

### Technologies

* Java
* Spring Boot
* MySQL
* Thymeleaf templates
* Bootstrap
* 3rd party resource for generating PDF

### What I'll Have to Learn

* For printing functionality we will need to either learn printing from HTML & CSS with resources like wkhtmltopdf or puppeteer or use JavaScript with a library such as pdfmake. 

* For getting state laws and other safety information we would likely need to learn to use webcrawler/scrapper tools. 

* Other ideas to expand our learning could be to include functionality for calling a contact through the site, retrieving and mapping emergency services near the house through Google Maps or the ability to upload pictures for contacts or family members.     

### Project Tracker
https://trello.com/b/avyUpuV4/liftoff-project
