# Javascript_pm_attack_demo
While carrying out a web pentest for a client, I found out the site was vulnerable due to how the site made use of the postMessage javascript method. Hence, this repository contains code that can be used for educational purposes to demonstrate the danger behind the insecure usage of the Javascript postMessage() method. 

# How to Use
To make use of this, the HTML file in the foler **ATTACKER** is for attacking the HTML file in **VICTIM**, **ATTACKER2** is for **VICTIM2**, you can make use of the files in each folder one after the other.
Use the Python code below to serve both the attacker's page and victim's page at different ports:
```bash
$ python3 -m http.server <port>
```
