# Instagram-bot
Instagram bot that tells you the name of user whom you follow, but they are not following you.

Requirements
-------------
- Python 3
- Selenium
- WebDriver for your browser

Installation
-------------
- #### Install Python by downloading it from [Python](https://www.python.org/downloads/ "Python")
- #### Install Selenium using command `$ pip install selenium`
- #### Selenium requires a driver to interface with the chosen browser. Google chrome, for example, requires chromedriver, which needs to be installed before this bot can be run. You can download it from below links.
  - `<Chrome>` : <https://sites.google.com/a/chromium.org/chromedriver/downloads>
  - `<Edge>` : <https://developer.microsoft.com/en-us/microsoft-edge/tools/webdriver/>
  - `<Firefox>` : <https://github.com/mozilla/geckodriver/releases>
  - `<Safari>` : <https://webkit.org/blog/6900/webdriver-support-in-safari-10/>
- keep this file in same directory where the **instabot.py** is in.

How to run
-------------
- set username and password variable to your instagram **user name** and **password** at line number **62 and 63** respectively and that's all 😁.

### Note: 
Instagram changes their front end frequently so this code may won't work.

If you have enabled **two factor authentication** then uncomment the line number **22 to 24** and then run the script. Execution sleeps for 40 seconds within that add the authentication code. After 40 seconds it will proceed further.     

