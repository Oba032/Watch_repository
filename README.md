## 1.1 Introduction
    This is a repository for the exam in the course "HEL-8048-1 25V Advanced data analysis and visualization using programming"
    I intend to investigate what health parameters influence the amount of calories burnt throughout the day, as well as how sleep affects calorie expenditure.

## 1.2 Variables
    # In this project i have chosen the following variables in my Apple watch:
    - Active Energy (kcal)
    - Apple Stand Hour (hours)
    - Heart Rate [Min] (bpm)
    - Heart Rate [Max] (bpm)
    - Heart Rate [Avg] (bpm)
    - Resting Energy (kJ)
    - Resting Heart Rate (bpm)
    - Sleep Analysis [Asleep] (hr)
    - Sleep Analysis [In Bed] (hr)
    - Sleep Analysis [Core] (hr)
    - Sleep Analysis [Deep] (hr)
    - Sleep Analysis [REM] (hr)
    - Sleep Analysis [Awake] (hr)
    - Step Count (steps)
    - Walking Heart Rate Average (bpm)
    # If you are curious about anything else you could add any variable of your wish from "Apple Health".
    

## 2. Requirements:
# 2.1 Hardware:
      1. An Apple Watch (Preferably a newer model such as the ULTRA S2)
      2. An Iphone with an active Apple-user (For extraction of data)
    These products have to be calibrated, connected, and enabled.
    Over the course of a given time of your choosing these devices will gather the types of data you want to assess.
# 2.2 Software:
    1. Health Auto Export (3rd-party application which can be downloaded from the App Store - https://apps.apple.com/us/app/health-auto-export-jsoncsv/id1115567069)
    2. Python Version 3.12.7 
    3. Anaconda Navigator - Jupyter Notebook, Github, and Aconda Prompt.

## 3. How to extract your data from "Health Auto Export":
# 3.1 Open the Application - Allow it to access your "Apple Health data".

# 3.2 Go to settings and change the Delimiter to "Semicolon", and change the unit to the one of your preference (I changed Active Energy from KJ to Kcal).

# 3.4 Choose the wanted Date range in the "Date Range" submenu, and "Export Format" should be set to "CSV"

# 3.3 Press either "Quick Export" or "Export" at the bottom of the main screen.

# 3.4 Share it or download the datafile to the computer containing the downloaded programs.
