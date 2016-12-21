# **Double Helix Drupal**

##### Epicodus Capstone 12.19.2016
#
##### By [Lisa MacCarrigan](https://github.com/lisamaccarrigan)
#
![screenshot of project main page](img/web-app.png)

----
### **Description**

This application utilizes Drupal 7.x, Ajax, two custom modules, and the use of functional and unit module testing. First, Ajax is used to display new biology terms without reloading the page; a custom module handles the ajax calls and loads content. Second, users can input a nucleotide sequence ('ACTG...') into a form and see the complementary sequence displayed. A custom module is used to create the form, validate input, and present the result to the user. Test Driven Development [through unit testing] was completed prior to writing the module logic. Once all unit tests were passing, the module was written, and then a functional test was run to make sure the entire user interface was working as expected.

----
### **Specifications**
| _Behavior_ | _Input_ | _Output_ |
|:---------------------------------------------------------------------:|:---------------------------------------------------------------------------:|:-------------------------------------------------------------------------------------------------------------------:|
| If the current index of one side has an A value, the other side has a T value | "A" | "T" |
| If the current index of one side has a G value, the other side has a C value | "G" | "C" |
| If the current index of one side has a T value, the other side has an A value | "T" | "A" |
| If the current index of one side has a C value, the other side has a G value | "C" | "G" |
| If the current side is AG, the other side is respectively TC | "AG" | "TC" |

----
### **Setup/Installation Requirements**

If editing:
* Clone this repository: https://github.com/LisaMacCarrigan/double-helix-drupal.git
* Set document root to the top level directory of the repository
* Import the database, called "dna", found in `sites/db-backup`
* Create a user for the database: username = "dna", password = "dna"
* Point browser to localhost
* Site maintenance account info: username = "dna", password = "dna"
* Open project folder ('double-helix-drupal') in Code Editor of choice

----

### **Known Bugs**

No known bugs.

----
### **Support and contact details**

For comments or questions, please email Lisa.MacCarrigan@gmail.com

----
### **Technologies Used**

* Drupal 7.53
* PHP
* MAMP Version 4.0.6
* MySQL Server
* phpMyAdmin Version 4.6.4

----
### **License**

*This application is licensed under the MIT license*

----
----
**Copyright (c) 2016 [Lisa MacCarrigan](https://github.com/lisamaccarrigan)**
