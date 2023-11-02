# essential
Create the python virtual environment:
python -m venv fastapi

Activate the created environment:
fastapi/Scripts/Activate.ps1

Install all dependencies for the project as listed:
pip install -r .\requirements.txt

Powershell might not respond. So set the execution policy running the following:
Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy Unrestricted

Enter the directory and check CRUD operations:
cd .\fastapi-crud-api\

After all the pre-requisites are installed, use this command (with administrator rights) to run the application:
uvicorn main:app

Then, in browser, write: http://127.0.0.1:8000
To see docs, write: http://127.0.0.1:8000/docs

Now utilize HTTP methods in Swagger UI to interact with the application locally.


