#nodejs-cucumber
This is the sample nodejs-cucumber framework 
## Tools used
Webdriverio - 4.13.2
Node - v8.9.1
NPM - 6.4.1

# Node_Modules
    "chai": "^4.1.2", - Assertion Library
    "pngjs": "^3.3.3", - To generate screenshot on error
    "wdio-html-format-reporter": "^0.2.9", - To generate html report (dependency on electron)
    "wdio-selenium-standalone-service": "0.0.10", - To download and install selenium-standalone
    "wdio-spec-reporter": "^0.1.5", - To generate json report
    "webdriverio": "^4.13.2" - To provide all browser related functionalities
    "wdio-cucumber-framework": "^2.2.7" - Integrated wdio-cucumber support
 
# How to start using 
1. Clone/Download the repo
2. Change the directory to nodejs-cucumber
3. run "npm i". It  downloads relevant stuff
4. run "npm run selenium". This will install and start selenium-standalone server (Keep this terminal open)
5. New terminal, run "npm run test". This will execute all tests and generate the report in reports directory
6. For every failed testcases screenshots will be captured and saved under errorShots directory


