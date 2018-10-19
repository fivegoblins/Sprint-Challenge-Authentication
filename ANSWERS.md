<!-- Answers to the Short Answer Essay Questions go here -->

1. What is the purpose of using _sessions_?
    Sessions are useful because the data is only stored in the broswer as long as the broswer is open; data is not stored in the server. There is also a higher storage limit on sessions than with cookies.
2. What does bcrypt do to help us store passwords in a secure manner.
    bcrypt hashes passwords, which means that passwords are not stored as plain text in the form that the users type them in, but rather bcrypt generates an entirely different string of characters that references the user's password and stores that hash, so that users' passwords can not be directly accessed by attackers.
3. What does bcrypt do to slow down attackers?
    It is possible for attackers to crack hashed passwords so bcrypt further slows attackers down by salting passwords, a process where an extra string is concatenated onto the password. Longer passwords become much more difficult to crack and if a password is long enough there comes a point where the time needed to crack it becomes prohibitively long.
4. What are the three parts of the JSON Web Token?
    The three parts of a JSON Web Token are the header, the payload, and the signature.
