<!--# Student-management-system
Student Management System using Flask and MySQL -->
_To_ _run_ _the_ _code_

Rquirements:-
    -Python
    -XAMPP
    -Text editor of your choice


To run:-
    -Extract all the files 
    -Open XAMPP and Start Apache and MySQL and click on admin on MySQL
    -on the server which just opened on a browser click on "New"
    -on "create database" title box give a DB name of your choice 
    -click on "import" and click on "choose file"
    -select the "student.sql" which you imported from the repository and scroll down and click on "go"
    -open "main.py" in text editor and on line 26 which has "app.config['SQLALCHEMY_DATABASE_URI']='mysql://root@localhost/students' replace the students with the name given by you in the xampp server for DB.
     (for ex: if you gave DB name in XAMPP server as studentdbms , replace student with studentdbms)
    -open terminal in your text editor 
    "It's better to install and run the code in virtual environament"
    -type "pip install virtualenv" and click enter
    -type "virtualenv myenv"
    -to activate the virtual environment  type "myenv\Scripts\acivate" and enter
    -now install flask by typing "pip install flask" in command prompt(do not exit virtualenv)
    -now install flask alchemy by typing "pip install Flask-SQLAlchemy" and enter
    -now install flask-mail by typing "pip install Flask-Mail" and enter.
    -now type "pip install mysqlclient" and enter
    -If you are using VS code install "HTML snippets" and "python" extensions
    -now install flask login by typing "pip install Flask-Login" on cmd
    -now type "cd student-management" and enter in cmd 
    -and type "python main.py" in cmd and enter 
    -You will get a server link starting with http://... 
    -copy that link and paste on your pc browser 
    - the project is executed now 
    
    
    
If you want to run again after installing all the required s/w:-
    -open cmd in the Student management file
    -myenv\Scripts\actiavte 
    -cd student-management
    -python main.py
