# Andrew and Scott's Gift Registry

Welcome to the future of gift registries. No longer will you be subjected to watching friends and family tap around like fools on Amazon's ancient site and app designs. Join Andrew and Scott's Gift Registry, and witness the power of social gift....uh...registering. 

## Getting the App
1. Download 64bit Git for Windows here, and install: https://git-scm.com/download/win
2. Open Command Prompt, and type git --version, and make sure it's installed.
3. Find a folder you'd like to store your code, and type "git clone https://github.com/ScottKnox/GiftRegistry.git"
4. Type "git checkout features/andrewBranch" and you'll be on a branch of code all your own. You can do anything on it, and it won't mess up our main branch's code. 

At this point, you can install VS Code, and open the folder containing our App's code. This editor will make it easy for ya to change things.

## App Setup

Close Command Prompt. 

1. Install Node on thy laptop: https://nodejs.org/en/download
2. Add Node to thy PATH: C:\Program Files\nodejs\
- Click Search, type "environment" and click "edit the system environment variables." Then, click "Environment Variables" and double click on "Path" in your System variables. If you don't see the above, just click "New" and insert it, and save. 
3. Open "Command Prompt" and change into the repo you cloned from github. 
3. Download the "Expo" app on thy cellular device.
4. In command prompt on your computer, type npx expo start --tunnel
5. In the Expo app on your phone, choose to Scan a QR code, and scan the one that the previous command brought up.

That outta do it! You've connected to a server running on your computer, that's hosting your mobile app in development mode. The app you see on your phone is a compiled native app, and the same process can be done for iPhone as well. 