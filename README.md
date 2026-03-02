# 🎂 Smart Birthday Mailer

Smart Birthday Mailer is a Python automation script that sends personalized birthday emails automatically using data stored in a CSV file and customizable email templates.

The program checks if today matches any birthday in the dataset, generates a personalized message, and sends it through Gmail using SMTP.

---

## 🚀 Features

- Automatically checks birthdays from a CSV file
- Sends personalized birthday emails
- Randomly selects a template for each email
- Uses SMTP for email automation
- Easy to customize and extend

---

## 🛠 Technologies Used

- Python
- Pandas
- SMTP (Gmail)
- Datetime module
- Random module

---

## 📁 Project Structure

```
smart-birthday-mailer
│
├── main.py
├── birthdays.csv
│
└── letter_templates
├── letter_1.txt
├── letter_2.txt
└── letter_3.txt
```

---

## 📄 CSV Format

The `birthdays.csv` file stores birthday information.

| Name | Email | Year | Month | Day |
|------|------|------|------|------|
| Mom | email@example.com | 1991 | 3 | 2 |
| Dad | email@example.com | 1990 | 7 | 9 |

---

## 📧 Email Templates

The templates are stored in the `letter_templates` folder.

**Example template:**

Dear [NAME],

Happy birthday!

All the best for the year!

Sudin


The `[NAME]` placeholder is automatically replaced with the recipient's name.

---

## ⚙️ How It Works

1. The script reads birthday data from `birthdays.csv`.
2. It checks if today's date matches any birthday.
3. If a match is found:
   - A random email template is selected.
   - `[NAME]` is replaced with the person's name.
4. The email is sent using Gmail SMTP.

---

## ▶️ Running the Project

1. Clone the repository

```
git clone https://github.com/sudinkatuwal7/smart-birthday-mailer.git
```

2. Navigate to the project folder

```
cd smart-birthday-mailer
```

3. Install dependencies

```
pip install pandas
```

4. Run the script

```
python main.py
```

---

## ⚠️ Security Note

Do **not** store your email password directly in the code when publishing to GitHub. Use environment variables or a `.env` file instead.

---

## 📚 Learning Goals

This project demonstrates:

- Python automation
- Working with CSV data using Pandas
- File handling and templates
- Email automation using SMTP
- Basic project structuring

---

<p align="center">
🚀 <i>अग्रे कथा भविष्यति</i>
</p>

<p align="center">
<i>The journey of automation continues...</i>
</p>
