# TimedUserEnum
This is a work in progress. It will spit out the times sorted in reverse order of post responses from login pages. Deviations *may* be used to determine valid usernames.

```
  _____ _             _ _____             _____
 |_   _|_|_____ ___ _| |  |  |___ ___ ___|   __|___ _ _ _____
   | | | |     | -_| . |  |  |_ -| -_|  _|   __|   | | |     |
   |_| |_|_|_|_|___|___|_____|___|___|_| |_____|_|_|___|_|_|_|
              Attacking Logins Using Time ...
```
## Usage
```
Usage:
	1. Find where credentials post to.
	2. Identify the username and password paramater names in the HTML form.
	3. Run command:

python3 TimedUserEnum.py (WORDLIST) (USERNAME PARAM) (PASSWORD PARAM) (POST URL)
```
