# openLCA Libraries User Guide
## What is a library?
The library feature in openLCA 2.0 and later versions enables the use of databases together without needing to import them on top of one another. A library serves as a read only database that can easily be combined with other databases. Processes and other elements that are part of a library database are not editable but can be utilized as part of processes or product systems in the main database. 
Libraries are beneficial for the current set-up of the Federal LCA Commons (FLCAC) as they allow for multiple distributed repositories to be self-contained, while still promoting interoperability between repositories. The connections provided by libraries benefit multiple repositories on the FLCAC. It’s important to note that libraries are currently an experimental feature in openLCA and will be updated based on user feedback and identified issues.

## Library Features
-	When a library is included in a database, a new “Libraries” folder appears in the database navigation pane (screenshot below). Libraries are also stored in your openLCA navigation pane, outside of individual databases.

![image](https://github.com/user-attachments/assets/dd3a327b-bc76-4583-bd0f-99993eac768f)
-	Library elements are incorporated into your database, but these elements are differentiated from main database elements by appearing in grey italics. Example below: 
-	No elements in the library database can be altered.
-	Library flows and processes can be used in processes in the main database.
-	Flows and providers in the main database can be replaced by library flows and providers by using the openLCA flow mapping or bulk replace features.
-	Product systems and results will include library processes and their product systems 

## Downloading a repository with a Library
When you download and import a repository that is connected to a library on the FLCAC you will be prompted to connect to the library as well. The url field should automatically populate with the library FLCAC url or you can choose to add a library from a file.

## Creating a process or product system 
To create a process with library flows, use the same process as when adding flows from your main database. The only difference is that flows and providers are indicated as library elements with this symbol:![image](https://github.com/user-attachments/assets/1ed6495f-9e0b-44cd-a3dd-95f7c9c13b91)
  /![image](https://github.com/user-attachments/assets/771adb5d-20fb-430b-b472-be087791dbd3). 

Product systems also generate similarly with library processes. Ensure that library providers are connected in your model graph and check the results to ensure that they the library processes were included.

## Exporting a Library
To share a database with a library, the library must be exported and shared separately. To export a library, navigate to the “Libraries” folder in the main openLCA navigation pane, right click on the desired library, and select export.

Importing a Library
To import a library into a main database, open the database by double clicking, right click the database name and select “Add a library”, then choose the desired library. The library can exist in the local version of openLCA or it can be imported from outside of openLCA. 
If datasets overlap across the library and the main database a “Tag conflicts” popup may appear (screenshot below). There are two options: “Update data sets” or “Update library tags only”. The first option will update all datasets with library elements, while the second option will only tag library elements if they’re unique to the library and will not overwrite duplicate elements in the main database. For FLCAC uses it is recommended that “Update library tags only” is selected. This allows data users to edit elements that are duplicated across the library and the main database.
![image](https://github.com/user-attachments/assets/37ed7e8b-729b-4ede-b11e-44b637fc2b96)
A “Data conflicts” popup may appear if “Update data sets” in the above step was selected, this indicates that datasets in the main database are being updated with library datasets.
![image](https://github.com/user-attachments/assets/bddcf416-d384-4335-a1a0-bab51034431f)
The library should now be added to the main database. A “Libraries” folder will appear in the main database and the library added can be opened. Library elements appear in this folder as well as in the main database. Library elements are italicized and a shade lighted than the main database elements.

## Creating a Library
-	Prepare the library database:
    -	Adjust the database that is intended to be transformed into a library as needed. Once this database becomes a library, edits are more difficult to implement.
    -	Delete all exchanges with an amount of zero, the matrices in a library do not currently support zeroes.
    -	Run a validation check on the database (Right click on database  “Validate”) and resolve any major errors. 

-	Transform the library database into a library element:
    -	Tools --> “Library export (experimental)”
    -	Assign a name to the library
    -	Set the Allocation Method to “As defined in processes”
    -	Selecting “Precalculate matrices” will speed up calculation times, but if this is selected then it is not recommended to choose “Only tag as library datasets” in a future step (this will cause issues with calculations)
    -	Selecting “With uncertainty distributions” and/or “Regionalized” will bring additional metadata into the library. These options will increase the size of the library and may slow down calculations. For FLCAC uses it is recommended to select these options to ensure metadata consistency.
    -	Press “Ok” and the database will be converted into a library. The database will remain the same and the library will appear in the navigation pane of openLCA under the “Libraries” folder.
