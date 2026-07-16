# DAY-11
 HTML Forms and Form Elements
## Date
15 July 2026
### Topics Covered
- HTML Forms
- `<form>` Tag
- Form Attributes
- `action` Attribute
- `method` Attribute
- GET Method
- POST Method
- `<input>` Tag
- HTML Input Types
- `<label>` Tag
- `<textarea>` Tag
- `<select>` and `<option>`
- Submit and Reset Buttons
- Creating Interactive HTML Forms
### Practical Work
Today we focused on creating HTML webpages that use forms to collect user information.
### Practical 1 – Music Festival Registration Webpage
Created a complete HTML webpage for an upcoming music festival. The webpage included:
- Festival banner image
- Event description
- Performer list
- Registration form
- Name, Email and Mobile Number fields
- Number of tickets
- Preferred seat selection
- Payment method selection
- Submit and Reset buttons
This practical helped us understand how HTML forms collect user information.
### Practical 2 – Restaurant Reservation Webpage
Created another HTML webpage for a restaurant.
The webpage contained:
- Restaurant name
- Restaurant image
- Introduction/About section
- Menu table with Dish Name, Category and Price
- Online table reservation form
- Customer details
- Reservation date and time
- Number of guests
- Seating preference
- Submit and Reset buttons
This practical demonstrated how forms can be used for online booking systems.
### Theory Notes
### HTML Forms
HTML forms are used to collect information from users. Forms allow visitors to enter data such as names, emails, passwords, phone numbers, feedback, booking details and many other types of information.
Forms are widely used for:
- Registration forms
- Login pages
- Contact forms
- Feedback forms
- Online bookings
- Surveys
- Admission forms
### `<form>` Tag
The `<form>` tag is the main container for all form elements.
It groups different input fields together and sends user data to the server.
Example
```html
<form>
...
</form>
```
### Form Attributes
### 1. action
The **action** attribute specifies where the submitted form data will be sent.
Example:
```html
<form action="submit.php">
```
### 2. method
The **method** attribute specifies how the form data is sent to the server.
Example:
```html
<form method="post">
```
### GET Method
- Sends data through the URL.
- Data is visible in the browser address bar.
- Suitable for searching and small amounts of data.
- Less secure.
Example:
```html
<form method="get">
```
### POST Method
- Sends data inside the request body.
- Data is not shown in the URL.
- More secure than GET.
- Used for login, registration and forms containing sensitive information.
Example:
```html
<form method="post">
```
### `<input>` Tag
The `<input>` tag is used to create different types of input fields.
Example:
```html
<input type="text">
```
### Common HTML Input Types
### Text
Used to enter normal text.
```html
<input type="text">
```
### Password
Hide typed characters.
```html
<input type="password">
```
### Email
Accepts only valid email addresses.
```html
<input type="email">
```
### Number
Accepts only numbers.
```html
<input type="number">
```
### Telephone
Used for mobile numbers.
```html
<input type="tel">
```
### Date
Used to select a date.
```html
<input type="date">
```
### Time
Used to select time.
```html
<input type="time">
```
### Radio Button
Allows selecting only one option.
```html
<input type="radio">
```
### Checkbox
Allows selecting multiple options.
```html
<input type="checkbox">
```
### File
Uploads files.
```html
<input type="file">
```
### Submit Button
Submits the form.
```html
<input type="submit">
```
### Reset Button
Clears all entered values
```html
<input type="reset">
```
### `<label>` Tag
The `<label>` tag gives a title or description to an input field.
Example:
```html
<label>Full Name:</label>
```
### `<textarea>` Tag
Used to enter long text such as comments, feedback or messages.
Example:
```html
<textarea rows="5" cols="40"></textarea>
```
### `<select>` Tag
Creates a drop-down list.
Example
```html
<select>
```
### `<option>` Tag
Defines the choices inside a drop-down list.
Example:
```html
<option>VIP</option>
```
### Buttons
### Submit Button
Used to submit the form.
### Reset Button
Used to clear all entered information.
### Key Learning Outcomes
- Learned how HTML forms work.
- Understood the purpose of the `<form>` tag.
- Learned the use of action and method attributes.
- Understood the difference between GET and POST methods.
- Practiced using different HTML input types.
- Learned to use labels for form fields.
- Created drop-down lists using `<select>` and `<option>`.
- Used `<textarea>` for multiline input.
- Built complete registration and reservation forms.
- Improved understanding of creating interactive webpages using only HTML.
### Conclusion
Day 12 focused on HTML Forms and user input. We learned how websites collect information from users using forms and practiced by creating two complete webpages—a **Music Festival Registration System** and a **Restaurant Reservation System**. This session improved our understanding of HTML form elements, input types, form attributes, and interactive webpage design.
