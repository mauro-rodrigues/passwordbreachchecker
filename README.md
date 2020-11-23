# passwordbreachchecker
Python script that uses haveibeenpwnd's API to check if a given password has been breached and if so, how many times. Can be used with command-line arguments or a text file containing multiple passwords, one by line.

You will need the requests module.
> pip install requests

Using checkmypass_terminal.py you will need to input your passwords as such:

> python3 checkmypass_terminal.py password1 password2 password3

Using checkmypass_textfile.py you will need to input your passwords as such:

> python3 checkmypass_textfile.py passwords.txt

