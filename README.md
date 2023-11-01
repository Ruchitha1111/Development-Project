# Development-Project
Attendance Tracker

This Python script is designed to automate the process of tracking and reminding students and staff about attendance in different subjects. It reads attendance data from an Excel sheet, allows you to input attendance information, and sends reminder emails to students and staff when students have low attendance or have exceeded the allowed number of leaves.

Prerequisites

Before using this script, ensure you have the following dependencies installed:

openpyxl: A library for working with Excel files. You can install it using pip:
pip install openpyxl

smtplib: A library for sending email messages. No additional installation is required for this as it's a part of Python's standard library.

Usage

1. Clone this repository or download the Python script.

2. Update the staff email addresses in the staff_mails list:

staff_mails = ['485@gmail.com', 'yyyyyyyy@gmail.com']
Replace the example email addresses with the actual email addresses of the staff members who should receive attendance reports.

3. Execute the script:
python Attendance.py

4. Follow the on-screen instructions to input attendance information. You will be prompted to enter the subject code and the number of absentees. If there is more than one absentee, you will be asked to input their roll numbers. The script will then update the attendance data in the Excel sheet and send reminder emails if necessary.

5. You can continue to input attendance information for different subjects by responding to the prompt at the end of each subject's input.

6. When you are done, type 0 to exit the script.

Configuration

The script uses Gmail for sending emails. You need to provide your Gmail credentials (your email and password) in the mailstu and mailstaff functions:

from_id = '1234@gmail.com'
pwd = 'tdbiwbj485'

Replace 'crazygirlaks@gmail.com' with your Gmail email address and 'ERAkshaya485' with your email password. Be cautious with your credentials, and consider using app passwords for added security.



