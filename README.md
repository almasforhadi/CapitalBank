# 💳 CapitalBank - Django Bank Management System

CapitalBank is a modern, user-friendly Django-based Bank Management System** designed to provide a seamless and secure digital banking experience.  
Users can register, log in, manage their profiles, deposit/withdraw money, request loans, and view transaction reports — all in one platform.

Every transaction is followed by an automated email notification, ensuring transparency and trust.  
The project features a responsive frontend built with HTML, CSS, and Bootstrap, offering a clean and professional UI across all devices.


## 🚀 Features

✅ User Registration & Login  
✅ Profile Management  
✅ Deposit & Withdraw Functionality  
✅ Loan Request System  
✅ Transaction History & Reports  
✅ Email Notification After Every Transaction  
✅ Secure Authentication System  
✅ Responsive UI (HTML, CSS, Bootstrap)  
✅ Admin Dashboard for User & Transaction Management  


## 🛠️ Tech Stack

- **Backend:** Django, Django REST Framework  
- **Frontend:** HTML, CSS, Bootstrap  
- **Database:** SQLite / PostgreSQL  
- **Language:** Python  
- **Version Control:** Git & GitHub  


## 📬 Email Notification System

After every successful transaction (deposit, withdraw, or loan approval), users receive an **email notification** with detailed information about the transaction.  
This feature ensures transparency and user trust.


## ⚙️ Installation & Setup

Follow these steps to set up the project locally:

#  Clone the repository
git clone https://github.com/almasforhadi/CapitalBank.git

#  Navigate to the project directory
cd CapitalBank

#  Create and activate virtual environment
python -m venv env
source env/bin/activate  # On Windows: env\Scripts\activate

#  Install dependencies
pip install -r requirements.txt

#  Apply migrations
python manage.py migrate

#  Run the development server
python manage.py runserver
