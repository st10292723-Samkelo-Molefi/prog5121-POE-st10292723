---Messaging System---

> Overview


This Java application is designed for the "PROG5121 POE" and provides the following functionality:

- User "Registration" with input validation.
- "Login" functionality using stored credentials.
- A  "Graphical Message System" that allows:
  * Sending validated messages.
  * Viewing sent messages.
  * Saving messages to a JSON file.

It is implemented using "Java Swing" for GUI components and uses the "org.json" library for managing message data.


> Features

Registration & Login

- Username must contain an underscore (`_`) and be no longer than 5 characters.
- Password must:
  - Be at least 8 characters long
  - Include a capital letter
  - Include a lowercase letter
  - Include a digit
  - Include a special character
- Cellphone number must match the pattern: `+` followed by 10–13 digits.

Messaging System

- Allows users to send messages via GUI.
- Messages must be:
  * 50–250 characters in length.
  * Sent to a valid phone number format: `+XXXXXXXXXXX`
- Messages are stored in a `message.json` file.
- Users can view a summary of all sent messages.




