# POE
This is the Programming POE for Csharp
I have to create a WPF application for a Contract monthly claim system
Part 1 is just the Project Planning and the prototype development.


Commits:
1. Initial commit with basic WPF project structure
   
* Added main window and dashboard layouts.
* Set up initial project files for the Claims Management system.

2. Added Lecturer Dashboard with claim submission form
   
* Created form for lecturers to input hours worked and hourly rate.
* Added fields for name, surname, and additional notes.
* Implemented data binding for claim submission.

3. Implemented file upload functionality for supporting documents

Enabled lecturers to upload PDF, Word, or Excel files as supporting documents.
Added validation and display of uploaded file name.

4. Added DataGrid to display submitted claims

Implemented dynamic DataGrid to show submitted claims in the Lecturer Dashboard.
Linked DataGrid to observable collection for automatic updates.

5. Created Coordinator Dashboard with claim approval and rejection buttons

Set up Coordinator Dashboard UI.
Added approve and reject buttons for claims management.

6. Implemented back button navigation for Lecturer Dashboard

Added a 'Back' button in Lecturer Dashboard to return to the main window.
Set up window transitions between main menu and dashboards.

7. Created Claims History page for viewing submitted claims

Implemented Claims History page.
Integrated claims display with pending, approved, and rejected statuses.

8. Added validation logic to claim submission

Added validation to ensure required fields (hours worked, rate) are filled in before submitting.
Provided user feedback via message boxes for missing information.

9. Enhanced UI and fixed file upload path issues

Fixed issues with file path handling during file uploads.
Improved layout and spacing on claim submission form.

10. Connected claims submission to history page and refined data binding

Linked claim submissions from the Lecturer Dashboard to the Claims History page.
Improved data binding between pages to display up-to-date claim statuses.
