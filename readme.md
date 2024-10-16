# Working Strucure of Linkdin
# UX
* providing a option of google and apple-id for loging
* side logo is a ux
* in password box show word is ux
* forget password is ux
* join know and footer bar is  ux
# UI linkdin logo is ui
1. Sign-in Buttons: 
Buttons for Continue with Google and Sign in with Apple 
2. Input Fields: 
Email/phone and password fields allow users to input credentials.
3. Logo : 
4. Sign-in Form Container: 
A white box with soft shadows, giving it a clean and modern look. It organizes the login elements in a clear, structured manner.
5. Buttons (Google and Apple Sign-in Buttons):  
these two button are offer to slec one is manually for login.
Input Fields (Email/Phone and Password):  this filed is requird to add data.
Forgot Password Link:
6. A blue clickable link under the password field for users who need to recover their password. It's a functional, visible text element with a distinct color to indicate it's clickable.
7. Sign-in Button:
A large, prominent blue button with white text ("Sign in") at the bottom of the form. Its size and color attract attention, making it the primary action users are expected to take.
# Frontend:
When a user enters their credentials (email and password) and clicks the "Sign in" button, the frontend (JavaScript) collects the data.
It might validate the input (e.g., check if the email format is correct) before sending it to the backend server.
It ensures that the user experience is smooth and interactive, like showing error messages if fields are empty or credentials are incorrect.
# Backend:
When the user submits their credentials, the backend server receives the request .
 the server check  the login request and checks the database to see if the entered email/phone and password match a registered user.
# Database :
he backend connects to the database to check the stored user data. The database contains users’ hashed and other relevant information.
If the user exists, the backend compares the entered password with the stored hashed password.
If the credentials are correct, the server sent back to the frontend to keep the user logged in.
