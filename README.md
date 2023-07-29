# SignUp_LogOut_Page
Working on the page 
There are two different pages "sign up" and "Profile"

Sign Up: consists of input fields and stores the inputs' value in local storage once the **Continue** button is pressed. 

From there the next page i.e. Profile page is loaded with the user's details inserted on the previous page. 

Profile: This page shows the key and values stored in local storage. The **LogOut** button is used to delete the access token and revert to the signUp page. 

NOTE: validator functions
>  required(username, email, password, cnfpassword): to check if all inputs are filled and both passwords are the same.
> 
> checkToken(): to verify if the token exists load the profile page.
> 
> checkProfile(): to check if no token exists in storage user is only able to load the signUp page.
> 
> removeToken(): this function removes the token from the local storage.
> 
![Screenshot 2023-07-29 200802](https://github.com/Rohit4352/SignUp_LogOut_Page/assets/65344659/aed039dd-fb58-474b-b7d3-46f8a43f3825)
![Uploading Screenshot 2023-07-29 201027.jpg…]()
