# Steps to use the file:
1. Download the repository
2. Set up the project with npm and install the required dependencies.
  - Change your project directory:
    cd "d:\Projects\vGHC-Slot-Checker-main"
  - Initialize the project with npm:
    npm init -y
  - Install the required dependency:
    npm install puppeteer
  - Then you can run your script:
    node checkRequestMeeting.js
3. run node checkRequestMeeting.js
  - Open your terminal/command prompt
  - Change your project directory:
    cd "d:\Projects\vGHC-Slot-Checker-main"
  - Run your script:
    node checkRequestMeeting.js
4. It will open the browser and navigate to the Grace Hopper Celebration exhibitor catalog. In the browser window that opened, you need to log in to your Grace Hopper Celebration account. Then go back to your command prompt/terminal. Press the Enter key to continue the script. 
5. The script runs continuously until you stop it with Ctrl+C. It checks every 5 minutes (you can change checkInterval). It alerts you immediately when spots are found. 


# Note: 
Enable cookies so you do not need to repeatedly log in
