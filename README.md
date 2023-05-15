# EyeVoc
have you ever thought of coding/ controlling your system without your hands,.. here is the Repo for one such thought.



Hi, guys!!!
============================
To Run EyeVoc in terminal: ||
============================
STEP 1 :
# make sure you already download Eviacam and install the EyeMouse and atleast once run
enable viacam.exe with following settings:
i) you keep speed according to your comfort of head rotation in X, Y axes;
speed ranging from 0 to 30--------- recommended 10
acceleration ranging from 0 to 5--- recommended 2-3
smoothness factor 0 to 8----------- recommended 3-5
Motion threshold 0 to------------ recommended 10
ii) If you want to restrict the mouse to some workspace limit you can, but usually ignore this
setting
iii) Enable Dwell click and it's time around 45-50 & select "beep on click" for good interaction
iv)you can ignore other settings.// above are mandatory
v) give administrative permissions whenever insisted or elses just disable it in settings so it
won't ask again and again
STEP 2: ( YOU CAN SKIP THIS STEP, IF YOU ONLY WANT TO RUN THE
APPLICATION(.exe file) )
# make sure that You have the latest python.exe interpreter and have following Libraries
downloaded
for Windows :
========= ONLINE version of EyeVoc
pyttsx3
$ pip install pyttsx3
pyautogui
$ pip install pyautogui
speech_recognition
$ pip install SpeechRecognition
wmi
$ pip install wmi
os
$ import os
re
$ pip install re
AppOpener
$ pip install AppOpener
Pythonping
$ pip install pythonping
=========== OFFLINE version of EyeVoc
pyttsx3
$ pip install pyttsx3
pyautogui
$ pip install pyautogui
VOSK
$ pip install vosk
wmi
$ pip install wmi
re
$ pip install re
os
$ import os
AppOpener
$ pip install AppOpener
STEP 3:
(CHANGE PATH ACCORDING TO YOUR SYSTEM)
● OFFLINE VERSION uses a vosk library folder, so to use it we need to provide it’s
complete path in Engine.py file(of offline version).{line no. 10}
So, update this path when you run the program in your system. Add the path to
vosk-model-samll-en-in-0.4.
● Also, OpenApps.py file change the path of eviacam.exe file.{line no. 71}
(Make this change in both versions).
(You can get the path of eviacam by opening Enable_viacam folder, then open bin
folder, then look for evicam.exe file.)
================================
To run the program in terminal: ||
================================
1. Online version :
Open src_code_online folder in vscode.
Open Main.py file and run it
2. Offline version :
Open src_code_offline folder in vscode.
Open Main.py file and run it
Link to all the voice commands :-
https://docs.google.com/document/d/19MFWQ_5MpEi7aJvZREQXF3sdn0hBGh0vE0YTHDRHv
Iw/edit
// whether online or offline/ run in terminal or run .exe-- the same strategies are applicable.
================================
To run EyeVoc Application: ||
================================
3. Online version :
Open EyeVoc_online_Application folder.
Scroll down, you will see a EyeVoc_online.exe file.
Doubleclick to run it
4. Offline version :
Open EyeVoc_offline_Application folder.
Scroll down, you will see a EyeVoc_offline.exe file.
Doubleclick to run it
================================
PROBLEMS YOU MIGHT FACE :
================================
● If while running the program, the mouseclicks(left click, right click) does not work, then
after you open eviacam, go to settings -> clicks , then check the allow dwell click box.
( you can see this is offline_demo video, while recording that we encountered same
problem. )
● While running exe file you might not be able to open other apps, this happens because
window os does not allow third party apps to acces or open your applications, so make
sure to give this access.
● If while using the online mode, you experience long delays then might your internet
speed is to very good or you are in a noisy background.
So we suggest to -
Run the application a quiet place
Switch to offline mode( i.e. run offline application )
========================================================================
=======================================
In Linux/MAC_OS :
pyautogui
$ python3 -m pip install pyautogui
pyttsx3
$ python3 -m pip install pyttsx3
speech_recognition
$ python3 -m pip install SpeechRecognition
wmi
$ python3 -m pip install wmi
AppOpener
$ python3 -m pip install AppOpener
NOTE: Since we only worked on windows, while running this program in different os might face
some importing packages issue.
If any of the packages aren't installing please follow the terminal suggestions and surf for a
compatible version of the library for your current python interpreter version

