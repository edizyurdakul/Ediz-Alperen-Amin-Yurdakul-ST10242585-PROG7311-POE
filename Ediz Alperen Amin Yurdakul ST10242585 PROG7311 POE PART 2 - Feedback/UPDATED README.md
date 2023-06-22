## Database Restoration

To restore the database backup, follow the steps below:

1. Locate the file named `ST10242585_EDIZ_YURDAKUL_PROG7311POE_PART_2.bak`.
2. Open SQL Server Management Studio and connect to the relevant database server.
3. Right-click on the desired database and navigate to "Tasks" > "Restore."
4. Select "Database" as the restore source and choose the option to restore from a backup file.
5. Browse for the `ST10242585_EDIZ_YURDAKUL_PROG7311POE_PART_2.bak` file and proceed with the restoration process.

## Connection String Update

To ensure proper connectivity, update the connection string in the project. Follow these steps:

1. Locate the file `DAL.cs` in the project folder `DataAccessLayer`.
2. Open the file and go to line 10.
3. Modify the connection string to match the new database connection parameters.

## Project Launch

To launch the project, perform the following steps:

1. Open the project in Visual Studio.
2. Press CTRL + F5 or click the "Start without debugging" button.
3. The project will start running, and you can proceed with using the application.

## Demo Login Details

Use the following login credentials for the demonstration purposes:

### Employee

- Email: [johndoe@example.com](mailto:johndoe@example.com)
- Password: password123

### Farmer

- Email: [janesmith@example.com](mailto:janesmith@example.com)
- Password: password456
