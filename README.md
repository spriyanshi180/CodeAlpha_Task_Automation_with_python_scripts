# 📧 CodeAlpha_Task_Automation_with_python_scripts
This project is a simple Python script that reads a text file, extracts all valid email addresses using regular expressions (regex), removes duplicates, and saves them to a new file.

# ✅ Features
- Extracts email addresses from any plain .txt file
- Uses Python's regex (re) module
- Removes duplicate emails
- Saves clean emails to a new file (emails_extracted.txt)
- Fully automatic and easy to use

# 📂 Files Included
- task_automation_with_python_scripts.py → The main script
- input.txt → A sample input file containing text with emails
- emails_extracted.txt → Output file with all extracted emails

# ▶ How to Run
1. Make sure you have Python installed on your system.
2. Put the raw text (with emails) into a file named input.txt
3. Run the script with this command:

```bash
python task_automation_with_python_scripts.py


4. Extracted emails will be saved in emails_extracted.txt.

🧪 Sample Input and Output

input.txt

Hello Priya, contact us at hr@codealpha.com or support@domain.org.
Backup: test.email@college.edu, admin123@company.in

Output → emails_extracted.txt

hr@codealpha.com
support@domain.org
test.email@college.edu
admin123@company.in
