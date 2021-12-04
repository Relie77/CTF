## TASK-1 What valid password can you use to access the "santa" account?

Load up burpsuite, and intercept the POST login request of the root page of the site. Send the request to intruder, take username as <b>santa</b>
and point the intruder to password value. Use any password wordlist, I recommend to go with [Seclist](https://github.com/danielmiessler/SecLists/blob/master/Passwords/Common-Credentials/10-million-password-list-top-500.txt). Start the intruder attack and after a minute you will find ```cookie``` password value returns 302 redirect.

Use ```santa``` as username and ```cookie``` as value and login successfully as santa.

## TASK-2 What is the flag in Santa's itinerary?

Once you successfully log in, you will find the <b>flag</b> in the dashboard.
```THM{SANTA_DELIVERS}```


<h3><b>That's it for Day- 4</b></h3>
