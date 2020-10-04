# SHEhacks
                                    Personal Health Assistant
Team leader:Esha goel (goelesha2001@gmail.com)
Team member 1: Vidhi garg (gargvidi1000@gmail.com)
Team Name: TechBay
In this project, we have made a personal health assistant using python and web scraping.
What does this project do?
This assistant will first ask about your details like name and age,then it will ask about your symptoms and then it will predict the disease.Then it will ask whether your condition is critical or not.If the answer is NO,then it will suggest us some measures which we are to be taken otherwise if your answer is YES,then it would ask which doctor you want to consult and then it will take you to Practo and whichever doctor you asked above would be automatically typed in the search bar and the results will be shown on your screen.
The process of opening the website and searching the doctor is completely voice controlled as the doctor which you want to search for will be automatically typed in the search bar and the results will be displayed.
This whole process is completely voice controlled and the web browser will be controlled by an automated software and the user need not to do anything except giving the voice commands.
How to execute?
To run this personal health assistant on your PC,save the jupyter notebook and the database in the same folder with the chromedriver extension downloaded in the same folder and then enter your location of downloaded chromedriver extension in the last cell in the line “driver = webdriver.chrome(‘your location’)”.

NOTE1:The database uploaded is quite small and this is just for the purpose of demo.We have created this database ourselves.For final product(which could be an app)we can create a bigger database with accurate symptoms and classifications of diseases,so that every person could make use of this app.

NOTE 2: Due to time constraints we could implement the project in jupyter notebook only.Given adequate time,we can overcome these steps of downloading these files and chromedriver and changing the path as it would be little time consuming.Instead,we can integrate all these things in an app and all these things would be integrated in the back-end and the user would be required to download only an app instead of multiple files.
