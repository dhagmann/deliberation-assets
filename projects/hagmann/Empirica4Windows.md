# How to set up Empirica for Windows user

For windows x64 user (Note it won't work on windows ARM64, i.e., surface dragonfly user)
Step 1:
https://docs.empirica.ly/getting-started/setup/windows-wsl-instructions-new
follow the instruction to install both WSL and Empirica

Step 2: 
Install Docker desktop (you need to keep it running for most of your tasks)

Step 3:
Install Node.js (https://nodejs.org/en/download)
But avoid the powershell method (it won't install Node.js globally).

Step 4: Check if node installation
In powershell: type 
node -v
(it should show its version)
npm -v
(if error appears, you need to add the installation folder of nodejs to your system path).
npx -v

Step 5
Open WSL, run
curl -fsS https://install.empirica.dev | sh
Then,
go to /mnt/d/deliberation-empirica folder, run
npm run build
npm run start
need to look for three things:
"Starting mock CDN server on part 9091"
"Starting etherpad in container on port 9001"
"Empirica (local build) server running: localhost:3000"

In my case, I have the dos2unix runner.sh and *.jsonl to succeed.

Step 6
Open WSL
go to /mnt/d/deliberation-assets folder, run
npx http-server --cors -a localhost -p 9090

Step 7
Go to localhost:3000/admin to create new batch
but the batch will fail becasue you have to convert: dos2unix *.md in your project folder!

THEN IT WILL WORK!

I got the help from:
https://chatgpt.com/share/685ab4a7-8920-800e-94cd-fdcb10a1e2f4
https://chatgpt.com/share/685adc89-2818-8011-857d-616d3aeb7899


===== Skip the entire session below ===
=== I was using it to run the localhost from deliberation-assets but it is on windows not on WSL ===
Step 5: 
Your "npm run build" script is trying to run builder.sh using sh, but on Windows, you need a shell environment that can interpret .sh scripts.
Here’s how to fix this: Use Git Bash (Recommended for Simplicity)
1.Install Git for Windows:
Download and install from https://gitforwindows.org/
2.Open Git Bash:
After installation, right-click in your project folder and select "Git Bash Here".
3.Run the build command in Git Bash:
npm run build
This should work, as Git Bash provides the sh shell.

Step 6:
Open WSL, go to /mnt/d/deliberation-empirica folder, 
run: empirica
Then localhost:3000/admin

Step 7:
RIght-click the folder deliberation-assets folder, select "Git Bash Here".
cd deliberation-assets
npx http-server --cors -a localhost -p 9090

This does not work. After I start a new batch in admin and go to localhost:3000. It says no game there.

====
