This project was my final group project for my web development course at TN Tech.

The premise for the project was to design an app that would be used by farmers to keep track of a "smart" chicken coop.

To start the program, open index.html

This will take you to a sign up page.

![image](https://github.com/Stechgit/Chicken-Coop/assets/127151101/337b2ecc-9973-4c30-b722-2cd139c2ddc1)


Input an email and password.  
The email must follow a valid email structure, i.e. johnsmith123@fakeemail.com.
The password must include a captial letter, number, and special character, as well as being at least 8 characters long.
Attempting to register with an account already created will  prompt the user that the account already exists.

User must then fill out the rest of the fields.  They are all required inputs, but do not validate the data so any text will work.

Clicking the register button after the fields have been inputed correctly will create an account and bring the user to the dashboard.  Upon loggin in, a session ID is created.

![image](https://github.com/Stechgit/Chicken-Coop/assets/127151101/0f9c00df-5dbf-4eb3-bb4c-2f2c38c3b6a1)


The landing page will show a broad array of data about the chicken coop.

Toggling the sidebar will allow the user to navigate to the settings page, display warnings, or logout.

![image](https://github.com/Stechgit/Chicken-Coop/assets/127151101/8344fdb7-40e6-4421-9482-469626848af2)


The settings page allows the user to manually update the sessings for their chicken coop.
The warnings button will display and upcoming weather warnings.
The logout button logs the user out of the application.

![image](https://github.com/Stechgit/Chicken-Coop/assets/127151101/7454b304-1461-4f5f-92c7-d839ac38e621)

When a user logs out, the information from the session ID is stored so that it appears when the user logs back in.  All settings and changes the user inputs are perserved.  Log in with the same account using the "Have an Account?" button at the top of the login page.  Any changes you made to the coop's settings will still be there.




