Refer to GDP report for instructions
Running the GUI
h. Initial setup
1. Download Visual Studio (VS) Code to the PC (https://code.visualstudio.com/download)
2. Download Python version 3.12.3 to the PC (https://www.python.org/downloads/). When initialising, make sure to add Python to PATH.
3. Download the following scripts and make sure they are in the same folder (https://github.com/jensman100/GDP_47.git).
a. Create_activity.py
b. Create_CPP_File.py
c. Create_Mission_Cycle.py
d. Main_Menu.py
e. running_mission_cycle_gui.py
f. Running_mission_cycle.py
g. running_the_gui.py
h. blank_mission_cycle.txt (save this in a folder within the main folder called ‘cpp_mission_cycles’).
4. Open VS Code and open a new terminal (Terminal -> New Terminal)
5. In the terminal type the following and wait for the process to finish before typing the next one:
a. pip install tk
b. pip install pandas
c. pip install pyserial
d. pip install matplotlib
e. pip install openpyxl
6. Set up VS code to run Python by selecting the correct interpreter. (Use the command ‘where python’ in the command line to determine the location of python).
vi. Running the code
1. Open VS code.
2. Open the folder in which you stored the codes (File -> Open Folder).
3. Open the file running_the_gui.py and press Run Python File (play button in the top right corner).
a. First window
The first window displayed is the main menu which is always returned to after finishing a task. Here you can choose the following options:
• Create activity – define or modify an activity which can be inserted into a flight mission cycle.
• Create flight mission cycle – create a flight mission cycle by adding previously defined activities and the number of cycles.
• Write to C++ - create the file required to upload to an Arduino from a flight mission cycle.
• Run mission cycle – once the C++ file is uploaded to the Arduino, the script will run the test. It will provide live updates on the force, RoM and temperature during the test.
b. Create Activity
Create a new activity.
1. Enter all the fields displayed in the window.
2. To check the fields are correct press the View button. Please note this will not save the activity!
3. To save the activity, press confirm.
Modify an existing activity.
1. Press the read activity button.
2. Select the activity you would like to modify from the drop-down list.
3. Press confirm.
4. Change the desired variables in the entry boxes.
5. To check the fields are correct press the View button. Please note this will not save the activity!
6. To save the activity press confirm.
c. Create Flight Mission Cycle
Create a new flight mission cycle.
1. Select the drop-down box labelled ‘Please select an Activity’ and choose the required activity from the list.
2. Press the add activity button to add the selected activity from the list of activities within the flight mission cycle.
3. Toggle the selected checkbox to add/ remove the activity from the mission cycle.
4. Change the number of cycles the activity is run by altering the entry.
5. Add more activities by repeating steps 1 to 4.
6. Alter the number of batch cycles the whole mission cycle will repeat, by changing the bottom entry.
7. To view the flight mission cycle, press show. Please note this will not save the flight mission cycle!
8. To save the flight mission cycle press save as and enter the name you would like to save it as.
Edit an existing flight mission cycle.
1. Press the open button.
2. Select the drop-down list labelled ‘Please select a Flight Mission Cycle’ and choose the flight mission cycle you would like to add.
3. Press open to confirm the import.
d. Write to C++
1. Select the drop-down list labelled ‘Click here to view mission cycle’.
2. Double-check check the mission cycle is correct. If so close the plot and select yes.
e. Run Mission Cycle
1. Open the desired mission cycle .ino file with the Arduino IDE. Upload the code to the Arduino.
2. Select the drop-down list labelled ‘Please select a mission cycle’. Select confirm to continue.
3. If not done so already, connect the Arduino to the PC,
4. Enter the com port number that the Arduino is connected to.
5. Press play/pause to initiate the test.
6. During the test:
a. Press play/pause to pause or resume the test.
b. Press stop to cancel the test

