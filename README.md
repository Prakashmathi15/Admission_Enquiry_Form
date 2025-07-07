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
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Admission Enquiry Form</title>
    <h1 align="center" style="color:rgb(243, 43, 7)">Admission Enquiry</h1>
</head>
<body>
<form method="post">

 <label for="name">Full Name</label>
 <input type="text" name="name" placeholder="Enter your name" required>
  <br><br>
 <label for="email">Email</label>
 <input type="email" name="email" placeholder="Enter your email" required>
 <br><br>

 <label for="phone">Phone Number</label>
 <input type="tel" name="phone" placeholder="Enter your phone number" required>
    <br><br>

    <label for="course">Program of Interest</label>
    <select name="course" required>
        <option value="" disabled selected>Select a program</option>
        <option value="Bachelors">B.E or B.Tech</option>
        <option value="Masters">M.E</option>
        <option value="Diploma">MBA</option>
        <option value="Certificate">Lateral</option>
        </select>
        <br><br>
        <button type="submit">Submit</button>
        <button  type="reset">Reset</button>
    
</form>
   
    
</body>
</html>
```
## Output:

## Result:
An Admission Enquiry Form using HTML that collects student details and message for institutional follow-up is successfully created using semantic and readable HTML.
