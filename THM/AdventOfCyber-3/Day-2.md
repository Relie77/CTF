## TASK-1 What is the name of the new cookie that was created for your account?

First of all, open the static site in new tab. Register for a new account. After you login to your account right click on the tab and click on inspect element. In the
```Application``` tab 'In Chrome', you can see a cookie named ```user-auth```

## TASK-2 What encoding type was used for the cookie value?

For this, copy the cookie value and go to [CyberChef](https://gchq.github.io/CyberChef/) and enter the cookie value. In the left panel search for <b>Magic</b>.
Use it to decode the value, It show's which encoding type is being used. The answer is - <b>Hexadecimal</b>

## TASK-3 What object format is the data of the cookie stored in?

Once it deocodes the value, it reveals that the date inside the cookies are stored in ```json``` data type. So the answer is <b>json</b>

## TASK-4 What is the value of the administrator cookie? (username = admin)

The decoded value will look like this ```{company: "The Best Festival Company", isregistered:"True", username:"test"}```. Change the username to "admin" and encode it
back to hex format using CyberChef or any other tool. the hex after manipulating the username looks like
```7b636f6d70616e793a2022546865204265737420466573746976616c20436f6d70616e79222c206973726567697374657265643a2254727565222c20757365726e616d653a2261646d696e227d```
Take the hex and again go back to the tab where the site is open, and change the cookie value from the previous hex with the new one. Once you reload the site, you will
be logged in as an administrator.

## TASK-5 What team environment is not responding?

Indicated by a red status symbol ``HR``

## TASK-6 What team environment has a network warning?

Indicated by yellow status symbol ``Application``

<h3><b>That's it for Day- 2</b></h3>
