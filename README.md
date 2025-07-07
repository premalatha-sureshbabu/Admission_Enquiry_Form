# Admission_Enquiry_Form
## Date:

## Objective:
To design a simple Admission Enquiry Form using basic HTML that collects student details such as name, contact, program of interest, and a message for further communication.

## Tasks:
#### 1. Set Up the HTML Structure:
Use ```<!DOCTYPE html>```, ```<html>```, ```<head>```, and ```<body>``` tags to define the document structure.
Set the ```<title>``` as "Admission Enquiry Form".

#### 2. Add a Page Heading:
Use ```<h1>``` to title the page as “Admission Enquiry”.

#### 3. Create the Form Layout:
Use the ```<form>``` tag to wrap all input elements. Set method="post" for structure.

#### 4. Add Input Fields:
Include the following fields using appropriate HTML elements:

Full Name

Email Address

Phone Number 

Program of Interest 

Message

#### 5. Add Submit and Reset Buttons:
Use submit and reset at the bottom of the form.

#### 6. Use HTML-only:
No CSS or JavaScript is to be included. Focus on structure and accessibility.

## HTML Code:
```
<html lang="en">
    <head>
        <title>Admission-Enquiry-Form</title>
    </head>
    <body>
        <h1>Admission Enquiry</h1>
        <form>
            <label for="fullname"> fullname: </label>
            <input type=text id="fullname" name="fullname">
            <br><br>
            <label for="Email"> Email: </label>
            <input type=text id="Email" name="Email">
            <br><br>
            <label for="Mobile"> Mobile: </label>
            <input type=text id="Mobile" name="Mobile">
            <br><br>
            <label>Gender:</label>
            <input type="radio" name="gender" value="male">Male
            <input type="radio" name="gender" value="Female">Female
            <input type="radio" name="gender" value="Other">Other<br><br>
            <label>DOB:</label>
            <input type="date" name="dob">
            <br><br>
            <label>Department:</label>
            <input type="radio" name="Department" value="CSE">CSE
            <input type="radio" name="Department" value="ECE">ECE
            <input type="radio" name="Department" value="Other">Other<br>
            <br><br>
            <label>Qualification:</label><br>
            <textarea name="qualification"></textarea><br><br>
            <label>Address:</label><br>
            <textarea name="address"></textarea><br><br>
            <label>Contact Mode:</label>
            <input type="checkbox" name="contactMode" value="Email">Email
            <input type="checkbox" name="contactMode" value="Phone">Phone<br><br>

           <input type="submit" value="Submit">

        </form>
    </body>
</html>
```
## Output:
![Screenshot (58)](https://github.com/user-attachments/assets/7d8598cf-4f68-430e-a0b9-2e254b20c162)

## Result:
An Admission Enquiry Form using HTML that collects student details and message for institutional follow-up is successfully created using semantic and readable HTML.
