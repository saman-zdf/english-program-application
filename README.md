# Refugee Language Tutoring Program Application.

## Purpose

---

The Refugee Language Tutoring Program (RLTP) partners volunteers with refugees and asylum seekers for the purposes of one-on-one, weekly English tutoring. The RLTP has two key objectives. First, to assist refugees and asylum seekers with the development of their English skills. Second, to build a community in which volunteers and refugees or asylum seekers develop meaningful relationships. To best accommodate the needs of the refugees and asylum seekers who participate in the RLTP, the RLTP employs a hybrid model. That is, tutoring is available online for one hour at any time during the week. In-person tutoring also runs on <TIME TO BE INSERTED> between <DAY TO BE INSERTED> at <LOCATION TO BE INSERTED>.

The purpose of this application is six-fold:

1. To process applications for both tutor and student positions.
2. To pair tutors and students based on their availabilities.
3. To provide training to tutors.
4. To provide tutors with materials they can integrate into their lesson plans
5. To enable tutors to submit their lesson plans for approval
6. To send automated reminders to tutors and students about their weekly tutorial sessions.

### How would this application work?

#### Students:

- A user can register/sign-up for the application and create a unique account
- A user will be asked for some details that can give an overview of his/her current English level
- a user will have the option of using a built-in translator to choose his/her language if any part of the survey form is not clear to them.
- while students fill up the survey form, they will be asked to schedule a date and time that would be convenient for the period of one hour of their study time. Time availability will be shown.
- A user will receive an email after submitting the form. This email should contain instructions on what would be the next step, also it should contain interview booking details with the organizer/administrator.
- After form submission students will receive an email for further instruction, such as their tutor's name, if their chosen time matches any tutor availability.
- They might have to download the pdf assignment and once they finished the assignment they can upload it to the application.

---

#### Tutors:

- A user can register/sign-up for the application and create a unique account
- A user will be asked for some details, s and schedule a time/ time slot that can show their availability and some other relevant questions.
- If the user has been accepted as a candidate they should be given access to the portal.
- On initial login, a user will/can/should have an automated pairing. If so, the details of a student must be blurred.
- The user will have three 20 minutes of video training modules, once he/she completes these modules they will have access to his/her student's details.
- users can use online resources for a study plan, such as video clips, articles, quizzes, etc.
- user must submit the lesson plans, what they did work on? what was the subject of the day? and how students respond to the study lessons.
- user can/should/will provide feedback at the each of the lesson and the details of feedback can/should/will be emailed to the students. That way students will know what part of their english they need to concentrate, like reading/speaking/writing.

---

## Functionality and Features

---

### Authentication

The application has an authentication system where users (students/tutors) need to sign in to the program to perform various tasks. This functionality provides features to handle actions that require users to be identified who they are, and what their role would be as a user. Once the user creates their account they will receive a verification email to verify their account.

### Authorization

The authorization system will handle protecting the personal profiles. It will give authority to the users (students/tutors) to perform actions regarding their role within the application. It also gives the authority to the administrator of the app to have full authorization on the application that gives an ability to perform any action that would be needed. Such as adding new users, removing users, or updating any upcoming events.

### Survey Form

1. Students:

- user will be asked several different questions such as details, level of English by prompting the different questions, their availability to schedule the time and once from's input filled, the user can submit.
- a student will have the option of using the built-in translator.

2. Tutors:

- user will be asked several different questions such as details, their availability to schedule the time, and once from's input is filled, the user can submit.
- automated interview session after form submission
- sending email to the user with interview details.

### Automated Pairing Tutor and Students

- It will pair up a student with a tutor according to their availability.
- If there is no match, the administrator will organize the matching to pair up the student with tutors.

### Online session

- We can use zoom or google meet for now.

### Reminder

- Send reminder to both tutors and students 24 hours before starting session and 15 minutes before starting. For this feature(I might need to use a third party with the scheduling functionality, AWS event-bridge, firebase cloud-function)
