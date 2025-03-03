This project contains a Java Servlet (LoginServlet) that handles user login with validation rules for both the username and password. It ensures that the user input meets specific criteria before allowing access to the application.

This Repo has a Main-UC branch which is updated with its most recent update and changes

📌 Main Merged with: uc1 --> uc2 
📌 UC1: - Create First Servlet web app Covered: ⭕ Create Servlet Project using Maven ⭕ Build a web app invoked by server
📌 UC2: - Create a Login Servlet with Validation
Covered:
✅ Created Login Servlet: A LoginServlet was created to handle user login functionality. It is mapped to /LoginServlet and uses the @WebServlet annotation with initialization parameters for the username and password.

✅ Servlet Initialization Parameters: The servlet retrieves the username (KUSHAGRA) and password (Kushagra@12) from the initialization parameters set via @WebInitParam.

✅ Username and Password Validation:

Username Validation: The username is validated using the regular expression ^[A-Z]{1}[a-z]{3,}$, which ensures the username starts with an uppercase letter followed by lowercase letters.
Password Validation: The password is validated using the regular expression (?=.*[0-9])(?=.*[A-Z])(?=.*[a-z])(?=.*[@#$%]).{8,20}, ensuring it includes at least one uppercase letter, one lowercase letter, one number, and one special character from @#$%, with a length between 8 to 20 characters.
✅ Login Success: If the username and password match the initialized values and pass validation, the user is forwarded to the LoginSuccess.jsp page.

✅ Error Handling: If the login fails, an error message is displayed, and the user is redirected back to the login page (login.html).


This repository serves as a great resource for project of Java, Servlet, and TomCat in a structured manner. 🚀 Feel free to explore!
