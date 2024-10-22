
> # Definition Of Done
> The DoD defines the criteria that each user story must meet to be considered “done”.
----------
### 1.  System Logging.
**Definition of Done:**
 - The registration form is developed and accessible on the registration page.   
   the registration page.
 - The form allows the entry of username, email, password and role selection (student or tutor).
 - All fields are validated (correct email format, secure password, etc.).
 - Upon submission, the data is correctly stored in the database.
 - A confirmation message is displayed to the user after successful registration.
 - Unit and integration tests are completed and approved.
 - Documentation is updated and approved.

----------

### 2.  Email Verification
**Definition of Done:**
- After registration, the system sends a verification email to the user.
- The email contains a unique and secure link for verification.
- Upon clicking the link, the user's account is marked as verified in the database.
- A confirmation message is displayed to the user upon successful verification.
- Unit and integration tests are completed and approved.
- Documentation is updated and approved.
    
----------
### 3.  Login

**Definition of Done:**

- The login page is developed and accessible.
- Users can enter their email and password.
- Credentials are validated against database records.
- Successful login redirects the user to the home page.
- A clear and specific error message is displayed if credentials are invalid.
- Unit and integration tests are completed and approved.
- Documentation is updated and approved.
  
----------

### 4. **Password Recovery**.

**Definition of Done:**

- The password recovery form is developed and accessible from the login page.
- Users can enter their registered email address to request password recovery.
- The system sends an email with a unique and secure link to reset the password.
- By clicking on the link, the user is redirected to a page where they can enter a new password.
- The new password is validated (security, minimum length, etc.) before being accepted.
- Upon successful reset, the password is updated in the database.
- A confirmation message is displayed to the user after successful reset.
- Unit and integration tests completed and approved.
- Documentation updated and approved.

----------

### 5. **Real-time messaging**

**Definition of Done:**

- The system allows sending and receiving instant messages between users (students and tutors).
- Messages are transmitted and displayed in real time without the need to reload the page.
- Sent messages are correctly stored in the database.
- The interface clearly shows when a message has been sent, received and read.
- The real-time connection is stable and handles loss or reconnection properly.
- Security measures have been implemented to prevent unauthorized access to messages.
- Performance and scalability testing completed, especially at high load.
- Unit and integration testing completed and approved.
- Documentation updated and approved.

----------

### 6. **New message notifications**

**Definition of Done:**

- The system displays real-time notifications for new messages received, even if the user is on another page of the system.
- Notifications include the sender's name and a snippet of the message.
- The user can directly access the message through the notification.
- Unread notifications are stored and displayed until the user reviews them.
- Notification preferences can be customized (enable/disable).
- Testing of notifications performed on different browsers and devices.
- Unit and integration tests completed and approved.
- Documentation updated and approved.
