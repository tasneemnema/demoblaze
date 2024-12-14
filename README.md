# demoblaze
this is a test for demoblaze.com where first i build the frame work as :
i created directory in resources file called features in that features file there is two files with extension (.feature) first one is for positive scenarios whis are :
sign up / log in and purchase two labtops and enter valid card credintials 
then i created pakage called (org.example) in that pakage there are three pakages which are (pages / stepdefs and testrunner)
in pages there are many classes we will start with home page class which has the code of the sign up with valid credintials and in step defs we has the class which is called signup 
in sign up class we have instance from the home page class and we called all functions in home page class 
then we have the class which is called login in pages we implemented the log in functions in it with valid credintials and then we have the class which is called login and purchase in that class we made instance from log in class and called the login class functions 
then we go to make the purchase by implemeneting the purchase class in pages directory and we made its instance and calling its functions in purchases class 
then we go to assertion so we have to go to cart page class in pages which has the implementations of the cart page where it has the assertion of the names and prices of the two labtops we purchased and then we go to the cart check class in stepdefs packages were we callled in it the cart page class functions after making the insatnce from the cart page class 
then we go to the total amount class where in it we double check (assert ) on how the total price is and as ususal we have the instance and calling its functions in total class 
the we go to the check out class in pages package where it has the implementation of clicking on place order and then sending keys for the credit card form to complete the purchase 
and the instance and the functions calling is in the placeorder and check out class 
this is for positive scenarion but for negative scenarios we have the following :
the negative sign up class is for negative sign up where it gives the credintials of already existing account and the calling of its functions and the instance is in sign up negative class 
and then we go to the loging in with negative scenario so we go to the wrong credintials class and its instance and functions is in credintials wrong class 
and for the last negative scenario we has to fill in expired credit card so its implementations is in check out negative class and its instance and functions is in nvecheckout class and for the report we have the code in runners and the report is generated perfectly 
