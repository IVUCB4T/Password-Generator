# Password-Generator

This code snippet is a simple web page that generates random passwords based on user input. Here's a breakdown of the key components:

1. **HTML Structure**:
   - The HTML file includes a title for the page and a container div that holds the elements for the password generator.
   - It includes input fields for the user to specify the length of the password and select which types of characters to include (lowercase letters, uppercase letters, numbers, and special characters).
   - There is a button to generate the password and a div element to display the generated password along with a button to copy it to the clipboard.

2. **CSS Styling**:
   - The CSS styles the page with a dark background color, white text, and centers the content vertically and horizontally using flexbox.
   - It styles the buttons, input fields, and password box to have a consistent look and feel.

3. **JavaScript Functions**:
   - generatePassword(): This function is called when the "Generate Password" button is clicked. It reads the user input for password length and character types, generates a random password based on the selected criteria, and displays it in the password box.
   - copyToClipboard(): This function is called when the "Copy Password" button is clicked. It creates a temporary textarea element, copies the generated password text to it, selects the text, copies it to the clipboard, and then removes the textarea element. Finally, it displays an alert confirming that the password has been copied.

Overall, this code provides a simple and interactive way for users to generate random passwords with custom criteria and easily copy them to the clipboard for use.
