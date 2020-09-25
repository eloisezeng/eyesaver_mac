# EyeSaver MacOS Automation Package

These scripts automate your computer to change your virtual background on Zoom. Download the EyeSaver WebApp so you can run these scripts when you press a button.

Main Advantages
---------------
- Appear to stare at the screen when your eyes are taking a break, or if you're doing something else
- Don't need to manually click the tiny buttons on Zoom

How to install EyeSaver: For Non-technical People
---------------
Install Node.js <br> Install Git <br> Install Python <br>
### Mac OS
Copy this into your terminal to install everything you need to run EyeSaver. 

git clone https://github.com/eloisezeng/eyesaver_mac
cd eyesaver_mac
pip3 install -r requirements.txt
cd ..
git clone https://github.com/eloisezeng/eyesaver_website
cd eyesaver_website
npm install
cd ..

### Windows OS
Copy this into your Powershell to install everything you need to run EyeSaver. 

git clone https://github.com/eloisezeng/eyesaver_windows
cd eyesaver_windows
pip3 install -r requirements.txt
cd ..
git clone https://github.com/eloisezeng/eyesaver_website
cd eyesaver_website
npm install
cd ..

### Run this command and search for 192.168.X.X:3000 (ip address) on your phone

Install Requirements for people interested in forking
---------------
pip3 install -r requirements.txt

Description of Python Files
---------------
- change_vb.py has functions that change the virtual background or do reactions (thumbsup/clapping)
- pixel_settings.py has functions that click certain positions on the screen. Users can change them in their code or in their computer app
- response.py is a python script that controls mouse clicking and key presses
- local_server.py is the server that runs response.py when a user presses a button

Contact
---------------
eloise.zeng@gmail.com

