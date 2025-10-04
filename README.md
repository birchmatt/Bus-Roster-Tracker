# Bus-Roster-Tracker
📊 Updated CSV Format:
Required Columns:

Bus Route - Route name
Last Name - Student's last name
First Name - Student's first name
Grade - Student's grade level
Leave - Y or N. Indicates whether the parent has okayed a student to be left by themselves at the bus stop

Example CSV File:
Bus Route,Last Name,First Name,Grade
Morning Route A,Johnson,Emma,5
Morning Route A,Smith,Liam,4
Morning Route A,Brown,Olivia,5
Morning Route B,Anderson,Isabella,3
Morning Route B,Taylor,James,5
Afternoon Route A,Thompson,Harper,4

How Students Are Displayed:
Students will appear as: "Emma Johnson (Grade 5)"
This format clearly indicates the grade each student is in when checking them off.
Features:

✅ Handles 4-column format (Bus Route, Last Name, First Name, Grade)
✅ Combines names properly - "FirstName LastName (Grade X)"
✅ Checkbox for headers - check if first row has column names
✅ Sorts students alphabetically within each route
✅ Error reporting - shows which lines had problems
✅ Handles quoted values - supports CSV with commas in names
✅ Validation - checks for all 4 required columns

Creating Your CSV:
In Excel/Google Sheets:

Column A: Bus Route
Column B: Last Name
Column C: First Name
Column D: Grade
Column E: Leave Y or N (new in Build)
Save As → CSV

The app will now properly parse your student roster files and display students with their grade levels!
