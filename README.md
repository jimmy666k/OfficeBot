# OfficeBot



## Introduction

OfficeBot, a cutting-edge office assistant revolutionizing document delivery within the workplace. Powered by the Bellman-Ford algorithm, traditionally employed in network optimization, OfficeBot navigates the office space with precision, calculating the shortest paths for efficient document transfers. In this project we choose Python for GUI and Prolog for Ai logic.


## Requirements

- Python 3.x
- SWI - Prolog


## How to run this project

Clone the repository:
```bash
  git clone https://github.com/TRP64011655/OfficeBot.git
```
    
Navigate to the project directory:
```bash
  cd OfficeBot/ui
```

Run the Python script:
```bash
  python main.py
```

Follow the instructions in the application:
- Select Destination
- Select Your Seat
- Select the Tray Number

## Files

- `deliverPackagePage.py` : This file is the page that shows the shortest path that the robot is taking.
- `historyFileManager.py` : This files is the file that manages history files.
- `historyPage.py` : This file is the page that shows the history of the OffieBot.
- `main.py` : This is the main file to run the file.
- `my_prolog.py` : This file is a bridge between prolog and python files
- `pageReject.py` : This file is the page that shows the user that the docuement has been rejected and the reason of it.
- `reachedPage.py` : This file is the page that shows the user that the package is delivered. 
- `returnPackagePage.py` : This file is the page that displays the return path when the package is being rejected.
- `StartPage.py` : This file is the start page of the program.

