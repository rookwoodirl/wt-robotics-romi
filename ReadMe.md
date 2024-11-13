1. Install WPILib for Java + VS Code
    Follow this guide: https://docs.wpilib.org/en/stable/docs/zero-to-robot/step-2/wpilib-setup.html
    It will run an installer that installs VS Code for you with all the WPI Lib extensions included.

    Something you don't have to do but something I want to document:
        * I created a new project for ROMI here
        * I had to add the line: "java.project.sourcePaths": ["src/main/java"] to .vscode/settings.json

2. Install Java:
https://www.oracle.com/java/technologies/downloads/?er=221886

Check java installed successfully:
    1.  Open VS Code
    2.  Go to "Terminal"
    3.  Run the command: java -version
    4.  If it tells you the version, you installed successfully. 
        If it says "Unable to locate a Java Runtime", try installing again.


3. git clone this repo by running the following command in the terminal:
    git clone https://github.com/rookwoodirl/wt-robotics-romi.git