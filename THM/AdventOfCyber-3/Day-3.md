## TASK-1 Using a common wordlist for discovering content, What is the name of the folder?

There's no need to run directory fuzzing, the directory name is easily guessable. 

## TASK-2 In your web browser, try some default credentials on the newly discovered login form for the "administrator" user. What is the password?

The administrator has a easily guessable credentials. Simply use burp intruder to fuzz the password, after fuzzing you will get ```REDACTED``` as username and password. And you will be logged in to the administrator dashboard.

## TASK-3 Access the admin panel. What is the value of the flag?

Once you login to the admin dashboard, flag is shown.
```THM{REDACTED}```

<h3><b>That's it for Day - 3</b></h3>
