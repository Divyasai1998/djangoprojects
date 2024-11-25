# djangoprojects
In the first step we are going to create the folder in the **c drive**Root directory:**"C:\Users\divya\PycharmProjects"**.
In the next step we are creating a directory in the c drive as **mkdir djangoprojects** so that directory will be created.
Now we are going to the open the directory in c drive as **cd djangoprojects**.
After that djangoprojects will be available in c drive then in the next step we are installing virtualenv using the command pip as **virtualenv install pip**.
By using the command **virtualenv venv**--> virtual environment is created.
We are going to activate the virtual environment by using command--> **venv\scripts\activate.**
next we will install django by using pip as **pip install django**.
check the django version either it supports with python or not using the command **django-admin version**.
Now we are going to start into our project as **django-admin startproject hello_project** in the virtual environment.
Now open cd hello_project as **cd .\hello_project\***
Now i am staring the **django-admin startapp HelloWorld_App** in the virtual environment.
Go to hello_project in that go to **settings.py file** and add **HelloWorld_App** in the installed apps.
Next go to **views.py** to get the **HelloWorld message**.
Now go to **hello_project** and write the code and then copy the same code in the **HelloWorld_App** and we will modify the code.
In the final step we are going to run the server as **python manage.py runserver**. Now we will get the link as http://127.0.0.1:8000/ next go to browser and paste the link then the messaged will be displayed as **{“Message”: “Hello World!”}*** .
