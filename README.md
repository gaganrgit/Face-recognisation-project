# face-recognition-based-attendance-system  

Line 1-9: We are importing the required libraries.
Line 11-12: Defining the Flask App.
Line 15-19: Functions that return today’s date strings to use in the program ahead.
Line 22-24: Initializing VideoCapture object to access WebCam.
Line 27-34: Checking if the required folders are in place or not, If not create them.
Line 37-39: A function that calculates the number of total registered users.
Line 42-46: A function that extracts the face from an image.
Line 49-52: A function that Identifies face using ML model.
Line 55-69: A function that trains the model on all the faces available in the faces folder.
Line 72-79: A function that extracts info from today’s attendance file in the attendance folder.
Line 82-91: A function that adds the Attendance of a specific user in our today’s Attendance file.

Routing Functions:

Line 96-100: Our main page routing function.
Line 103-126: This function will run when we click on Take Attendance Button.
Line 129-160: This function will run when we add a new user.
Line 163-165: Our main function which runs the Flask App.
