# login using Shared Preferences

Shared Preferences and more

## problem statement

create an android application with THREE activities.

First activity should have two buttons such as `Log in` and `Registration`.
1. by clicking the `Log in` button, it should bring user to the Log in screen
2. by clicking the `Registration` button, it should bring user to registration page
3. create a registration page of fields `Username`, `password`, `email`, `phone number`, `course`, `gender`, `age`
4. apply necessary `Validations` to it:
    - Make all the fields as mandatory
    - Password must contain minimum of 6 characters (upper, lower, number)
    - Phone should accept only 10 numbers
    - Email should follow the standard format `@xyz.COM/EDU/IN/ORG`
5. use `Shared Preferences` that stores `username` & `password`, and retrieve them for login
