# goElectric by mapit.space
### Setup Instructions for the mapit.space submission

## Setup
### URGENT: The way we have this set up right now utilizes clientID/clientSecrets that must be set up manually to work on your local web server. Please do not push proxy/PHP/proxy.config to the final submissions repository with the clientID/clientSecrets fields filled in.

1. Unzip the submission folder.
2. Copy contents to the web server folder (will be denoted in subsequent steps as <www folder>).
3. Navigate to <www folder>/proxy/PHP/
4. Open "proxy.config" with your favourite text editor (ex. notepad++)
5. Go to line 5, featuring "allowedReferers"
6. Replace "localhost:41471" with your local web server name
7. Save proxy.config
8. Open your favourite web browser and enter the url of your local web server (ex. localhost:41471)
9. Navigate from the application homepage (index.html) to "Explore" in the top right hand corner of the screen
10. Observe the web map application (goelectric.html)


### Issues?
Please contact alyshav@sfu.ca.


### Resources for running local development web environments:
* Windows web development environment http://www.wampserver.com/en/
* VS code: https://code.visualstudio.com/
