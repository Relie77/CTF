## Task-1 - After finding Santa's account, what is their position in the company?

Try changing the user_id value in the address bar, and you'll see that the web application tries to load another user's information. Try different numbers between the values 1 - 20 
until you find a user who could have been responsible for the tampering on the system. Tampering the user_id with value 1 shows Santa's account, with the position of ```REDACTED```  

```
https://inventory-management.thm/activity/?user_id=1
```

## Task-2 and Task-3

Do the same as above, try to tamper the value from -1-20 and eventually you will end up finding all the other accounts, with their positions.

## Task-4

After reverting the changes "Grinch" made to the inventory management system, you get a flag.
```THM{REDACTED}```

<h3><b>That's it for Day- 1</b></h3>

