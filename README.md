# pomodoro
Welcome to pomodoro project!

Hi im tric0, and pomodoro is a timer with break time designed in Python.

                                                      INDEX
                                                
                                                  1 - Installation guide
                                                    1.1 - Windows
                                                    1.2 - Linux
                                                  2 - Python libraries
                                                  3 - Avaible functions


1 - INSTALLATION GUIDE

    If you want to install it make sure to follow the instructions below to make it work.
    
   1.1 -  Installation process on WINDOWS:

            Clone the repository or download the ZIP code. Run pomodoro.exe.
    
   1.2 -  Installation process on LINUX: 

            Clone the repository from GitHub in the actual route:
            - git clone https://github.com/tric0ma/pomodoro.git
        
            Change directory and go inside the new folder called "getyt":
            - cd pomodoro
            
            Activate virtual environment:
            - source venv_pomodoro/bin/activate
          
            Install python libraries if you dont have requirements.txt:
            - pip install PySide6
        
            Run the python script. You have to be in getyt directory:
            - python pomodoro.py

2 - PYTHON LIBRARIES

    In this project we are using the next modules:

    - PySide6.QtCore: (QTimer, Qt, QUrl)
    - PySide6.QtGui: (QFont, QIcon)
    - PySide6.QtMultimedia: (QSoundEffect)
    - PySide6.QtWidgets: (QApplication, QWidget, QPushButton, QLabel, QGridLayout, QSlider)

3 - AVAIBLE FUNCTIONS

    In the actual version of pomodoro you can use the following functions:

    - GUI for pomodoro designed with PySide6
    - Set pomodoro timer from 1 to 60 minutes
    - Set break timer from 1 to 30 minutes
    - Start, Stop, Resume and Reset buttons for global timer
    - Green screen means break time
