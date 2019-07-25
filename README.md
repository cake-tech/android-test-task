# Here is described test tasks for a android dev.

Need to implement three screens: create PIN code screen, authentication by PIN code screen and menu screen.
PIN code is sequence of integers. PIN code length is 4 digits.

## Create PIN code screen
Create PIN code screen should give ability for user to create (set) own PIN code.
For successful creation PIN code user will be needed to enter same PIN code twice and show a message with text "Your PIN code is successfully created".

![alt-text-1](./images/create-pin-first-step.png "Fist step") ![alt-text-1](./images/create-pin-second-step.png "Second step")
![alt-text-1](./images/create-pin-process.gif)

## Authentication by PIN code screen
Authentication by PIN code screen should give ability to enter user's PIN code. Entered user's PIN code should be checked for equality with previus created (on Create PIN code screen) user's PIN code. If authentication by PIN code will be succesful user should get a message with text "Authentication success", or it was faild user should get a message "Authentication failed".

![alt-text-1](./images/auth.png)
![alt-text-1](./images/auth-process.gif)

## Menu screen
Menu screen should have two buttons for navigation to Create PIN code and Authentication by PIN code screens.

