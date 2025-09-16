## 💻 Excel File Preparation – Description of Work Done

During the preparation of the Excel file, the following steps were taken to clean, organize, and analyze the data:

Removing Extra Blank Rows:
After copying the student names from another folder, two blank lines appeared between each name. This issue was resolved by using the Filter feature in Excel, selecting the (Blanks) option, and deleting the empty rows.

Alphabetical Sorting of Names:
The names were not initially in alphabetical order. The Sort A to Z function was used to arrange the names correctly in the “أسم الطالب” column.

Calculating Total Scores:
The total for each student was calculated using the SUM function across the following columns:

اللغة العربية

اللغة الإنجليزية

رياضيات

فقه

The formula was then dragged down to apply it to all students.

Calculating Averages:
The AVERAGE function was used to compute the average grade for each student based on the same subject columns. The formula was also filled down the column.

Pass/Fail Determination:
To determine whether the student passed, the following formula was used in the “النجاح” column:
=IF(H3>=200, "راسب", "ناجح")
This logic checks if the total score is 200 or more.

🔹 All subject labels were kept in Arabic to match the original dataset structure.

## 📥 To download the file:

Click the file name on the left (Student Grades Report.xlsx)

Then click "View raw" in the middle of the page

The download will begin automatically
