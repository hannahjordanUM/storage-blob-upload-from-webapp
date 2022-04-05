Dependencies: (commands for Powershell/CMD)
    pip install Flask
    pip install python-dotenv
    pip install azure-storage-blob
    Azure Storage Connection String

To run this app, make sure you are in this directory of the app, 
in the terminal use the "flask run" and it will detect the "app.py" then run it
It will output local dev server    


How to get Storage Account String

Azure Home > storage account > click storage account for app > Access Keys (Security + Networking) > under "Key 1", show all, then copy connection string from Key 1. 

Go to ".env" file and replace string with connection string.
if this don't work, may have to manually input within our environment (See command below)

Can be included in an EOF tag within terraform when deploying to automate this in the future.

powershell command:
$Env:AZURE_STORAGE_CONNECTION_STRING = "<Your connection string>"

