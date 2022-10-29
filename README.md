# user-management-system
User can login into the website by submiting email id phone no and a One time password is generated in backend which is must required for login and user can logout also.


#dependency

"body-parser"
"express"
"express-handlebars"
"nodemailer"
"nodemon"


## Setup
1. Clone this repository.
2. Install dependencies: `npm install`.
3. Run the project:  nodemon app.js
Visit localhost:3000 on your browser

#Working 

Once Detail is filled in form otp is generated on backend and write the same otp in verification leads to successful login .If otp is not correct we saw a message regards incorrect otp we can resend otp and again try the otp
We can also successfully logout by clicking on logout button.



