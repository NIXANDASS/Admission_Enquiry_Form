# Admission_Enquiry_Form
## Date:07/07/2025

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
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Saveetha Engineering College - Admission Enquiry</title>
</head>
<body align="center">
    <h1>Admission Enquiry Form</h1>
    <form>
        <div>
        <label for="fullname">
            FULLNAME

        </label>
        <input type="text" placeholder="Enter your name" required>
        <br><br>
        <label for="email">EMAIL ID</label>
        <input type="email" placeholder="Enter your email">
        <br><br>
        <label for="mobile number" >MOBILE NUMBER</label>
        <input type="number" name="mobile number" placeholder="Enter your mobile no" min="100000000" >
        <br><br>
        <label for="gender">GENDER</label>
        <input type="radio" name="GENDER">Male
        <input type="radio"name="GENDER">Female
        <br><br>
        <label for="dob">DOB</label>
        <input type="date" name="dob">
        <br><br>
        <label for="dept">DEPARTMENT</label>
        <select name="dept" >
            <option >--</option>
            <option >CSE</option>
            <option >IT</option>
            <option >AIML</option>
            <option >AIDS</option>
            <option >ECE</option>
        </select>
        <br><br>
        <label for=" Academic Qualification">ACADEMIC QUALIFICATION
        </label>
        <br><br>
        <textarea rows="5" cols="35">

Type your Academic Qualification
        </textarea>
        <br>
        <br>
        <label for="Address">ADDRESS
        </label>
        <br><br>
        <textarea rows="3" cols="40">

Type your Address
        </textarea>
        <br>
        <br>
        <label for="contact mode">Preferred Mode of Contact </label>
        <input type="checkbox" name="contact mode">Email
        <input type="checkbox" name="contact mode">Phone
        <input type="checkbox" name="contact mode">Whatsapp
        <br>
        <br>
        <button type="submit">Submit</button>
        <button type="reset">Reset</button>
        
    </form>
</body>
</html> 
```
## Output:

## Result:
An Admission Enquiry Form using HTML that collects student details and message for institutional follow-up is successfully created using semantic and readable HTML.
