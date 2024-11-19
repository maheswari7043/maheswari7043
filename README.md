- 👋 Hi, I’m @maheswari7043
Step 1: Prepare Data
Open Excel Spreadsheet: Open an Excel spreadsheet (e.g., Microsoft Excel, Google Sheets) on your computer.

Record Information: Record the first name and last name of the recruiters or employees found on LinkedIn in your Excel spreadsheet. This will ensure that you have accurate data to use in the email generation process. In the spreadsheet, create columns for "First Name," "Last Name," "Email,", "Company Name" and "Desingation" Enter the relevant information for each recruiter or employee in the respective rows. If the recruiter or employee's email address is available, enter it in the "Email" column. If not, leave the "Email" column blank.

Step 2: Update Resume File Name
Locate Your Resume: Find your resume file on your computer. Make sure it's in PDF format and is named appropriately (e.g., "YourName_Resume.pdf").

Step 3: Update Environment Variables
Create .env File: Create a new text file on your computer and rename it to .env (make sure it doesn't have a .txt extension).

Enter Email Credentials: Open the .env file with a text editor (e.g., Notepad, TextEdit) and enter your email credentials in the following format:

EMAIL_USERNAME=your_email@gmail.com
EMAIL_PASSWORD=your_email_password
Replace your_email@gmail.com with your email address and your_email_password with your email password.

Step 4: Update Email Template File
Choose Email Template: Decide whether you want to use a formatted or plain text email template.

Open Email Template File: Locate the email_template.txt file in the project directory and open it with a text editor.

Customize Email Content: Modify the content of the email template to include a personalized message to recruiters or employees. You can include placeholders like {first_name}, {last_name}, {company_name}, and {email} to personalize each email.

If you want to send plain text emails, leave the formatting as is.
If you want to format your emails (e.g., bold, italics), uncomment the relevant lines in the template file and customize the formatting as desired.
Step 5: set the virtual enviorenment using cmd on vs code python -m venv venv 
step 6:activate the venv using this command .\venv\Scripts\activate
step7 : if you get this error The error you're encountering is related to PowerShell's execution policy settings. By default, PowerShell restricts the execution of scripts for security reasons. To activate a virtual environment (venv) in PowerShell, you need to adjust the execution policy temporarily or permanently.
the type this command on vs code Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
now again run step 6: command 
step 8: pip install -r requirements.txt
step 9: python main.py the choose option accordingly and as well as before choosing anything make sure you have date in recurirter excel sheet

<!---
maheswari7043/maheswari7043 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
