<h1>Requests & Flask</h1>

<h2>Task definition and requirements</h2>
Develop a basic Flask server that utilizes a database created with the SQLite Sample Database (available at https://github.com/dtaivpp/car_company_database). You can find a tutorial on integrating Flask with SQLite at https://pythonbasics.org/flask-sqlite/.
 
The server should expose API endpoints that allow user to retrieve, save, edit and remove data. For example, you could create endpoints that retrieve all customers that bought Ferrari from Priority X dealer and paid more than 20000$. Allow user to create new rows of data using POST method, update it with PUT method and delete it with DELETE method. 
Required endpoints to handle:
 
CRUD for customers with filtering (search parameters: brand, dealer, purchase price, model)
CRUD for models with filtering - display possible colors for each model (search parameters: car color, brand, price)
 
None of the filtering parameter are required to perform request, they are optional and only for narrowing results
If no results are found return empty list of items
Return responses in JSON format.
 
It would be really nice if you provided UI for this solution.


<h2>SQLite installation guide for the other developers</h2>

1. Enter this webpage: https://sqlite.org/download.html
2. Download precompiled binaries of tools (depending on your machine Mac/linux/windows). For windows for example, download this: sqlite-tools-win-x64-3490100.zip
3. Create a new folder in C: directory. Name it "sqlite".
4. Extract the contents of downloaded zip file into new created folder.

<i>Following instructions are only for Windows machine</i>
1. Press windows symbol and type: `Edit the system environment variables`
2. Press `Environment Variables`
3. In user variables for <your-username> window, double click on `Path`
4. Press on `New`
5. Write `C:\sqlite` (it should be the same path to the folder you created)
6. Press OK
7. Close the window
8. Open Command Prompt (you can do that by typing `cmd` in Windows search bar and enter)
9. Type `sqlite3` and press enter
10. You should see something like this. It means that it is installed properly: 

```
SQLite version 3.49.1 2025-02-18 13:38:58
Enter ".help" for usage hints.
Connected to a transient in-memory database.
Use ".open FILENAME" to reopen on a persistent database.
sqlite>
```
If not, write to Konrad Piotrowski on Teams or Messenger :)

<h2>Solution description</h2>

<i>TO BE COMPLETED</i>
