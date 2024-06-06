Adebola_fale omowonuola Richard(0849841)
Web app created w/ VS2022 .NET 7

1303
Recreated the ASP .NET MVC Core application
Using .Net 7,no authentication

Ran the program, Confirmed the default works:
https://localhost:7212/

Modified the index.cshtml title to MVC MOVIE by replacing the default title WELCOME
Created README.txt for documentation.
Ran the application again to confirm the changes


1325
I made sure icompleted  Part1 of the tutorial,before starting with part2
Part2 - I add a Controller

1343
I Commented the default index method which is returning to class view()
1345
I added a new index method after, i changed the content to "This is my default action..."
Executed the program and i Confirmed the changes worked:
https://localhost:7212/HelloWorld

1357
I added a new method called welcome with the content "This is the Welcome action method"
1400
Executed the program, and Confirmed the changes worked
https://localhost:7212/HelloWorld/welcome

1420
Changed the Welcome method to include both(name,numtimes)
Executed the program, Confirmed the changes works:
https://localhost:7212/HelloWorld/welcome?name=rick&numtimes=1

1440
changed the Welcome method to (name,ID)
https://localhost:7212/HelloWorld/Welcome/3000?name=Andrew
1505
Replaced the the index method in the controller class to call controller view method
1510
confirm the changes
1515 
stopped for the day 
23/05/2024 1309
starting from  where i stopped 
checked if all codes are still running perfectly
1315
i started part 3
added a view saved with index.cshtml
1330
comfirmed the view added
changed the title footer and menu
added a command to pass data from controller to view
saved my changes
1455
i created a loop 
saved the settings
1505
confirmed the change using url https://localhost:{PORT}/HelloWorld/Welcome?name=Rick&numtimes=4
1507
started part 4
1508
added a data model class
1513
added Nuget packages
1516
used the scaffolding tool to produce create, read update and delete
1520
created a database

timestamp
20240523185854_InitialCreate
1535
tested the app
1335 2024/05/30
I confirmed if my code was still running properly and checked if there is no code error
I created a new class in the model and named it seed data
1340
i added the seed initializer
i executed the program and confirmed the code worked 
//the code was confirmed working
Deleted all the records in the database using the delete link
called the code in the Program.cs file, so the seed method runs.
part 5 ended
1347
i started part 6
i modified the code in models/movies.cs to make release date seperate words
1358
i added a search capability to be able to search for a movie by either a movie name or genre
1400
i executed the program and confirmed the code worked 
the code worked out well
1410
Generated The Edit, Details, and Delete links using the Core MVC Anchor Tag Helper in the Views/Movies/Index.cshtml file.
i recalled the format for routing set in the Program.cs file
i exected the code and there was an error
1425 
i had to reconfirm the code for generating the edit detals and delete link to solve the issues
ended part6
1435
started part seven 
i added a search compability inside the movie controller
1440
i executed the program and confirmed the code worked 
I Navigated to /Movies/Index and Append a query string aftter the index ?searchString=Ghost to filter the movie
i Changed the parameter to id and change all occurrences of searchString to id
1450
i executed the program and confirmed the code worked 
it worked perfectly well
1505
2024/06/06
 i executed my program to see if it is still running perfectly 
 started part 8
 In an ASP.NET Core MVC application, add a new field.
added the "Rating" field.
The new field was migrated to the database.
I was able to create, modify, and view movies using a Rating field after running the software.
Part 8 is finished.

git repository was created.
Click git from Visual Studies.
"Local repository" should be selected.
Choose the clone repository.
christened it 
gave my git credentials
Project uploaded.








