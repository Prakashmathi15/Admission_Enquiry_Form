# Admission_Enquiry_Form
## Date:07-07-2025

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
  
    <title>Admission Enquiry Form</title>
    <h1 align="center" >Admission Enquiry</h1>
</head>
<body>
<form method="post">

 <label for="name">Full Name</label>
 <input type="text" name="name" required>
  <br><br>
 <label for="email">Email</label>
 <input type="email" name="email" required>
 <br><br>

 <label for="phone">Phone Number</label>
 <input type="tel" name="phone"  required>
    <br><br>

    <label for="course">Program of Interest</label>
    <select name="course" required>
        <option value="" disabled selected>Select a program</option>
        <option value="Bachelors">B.E or B.Tech</option>
        <option value="Masters">M.E</option>
        <option value="Master">MBA</option>
        <option value="Lateral">Lateral</option>
        </select>
        <br><br>
    <label for="message">Message</label>
    <textarea name="message" rows="4" cols="50" required></textarea>
    <br><br>
        <button type="submit">Submit</button>
        <button  type="reset">Reset</button>
    
</form>
   
    
</body>
</html>
```
## Output:
<img width="952" alt="image" src="https://github.com/user-attachments/assets/217c474c-7b12-47b9-b230-01c934231c11" />



## Result:
An Admission Enquiry Form using HTML that collects student details and message for institutional follow-up is successfully created using semantic and readable HTML.
