# 💸 Personal Finance Tracker

A comprehensive financial management web application built with Django. Track your income, expenses, savings goals, and budget targets through an intuitive, responsive interface.

## ✨ Features

### 👤 User Management
- Secure user authentication system
- Profile management with customizable user information
- Password reset functionality

### 📊 Dashboard
- Overview of financial health with key metrics
- Visual representations of spending patterns
- Quick access to recent transactions

### 💰 Transaction Management
- Record income and expenses with detailed categorization
- Attach receipts to expense records
- Filter and search transaction history
- Financial summary and balance calculation

### 🏷️ Financial Categories
- Create and manage income sources
- Set up expense categories with monthly budget limits
- Track spending against budget limits with visual indicators

### 🎯 Budget Goals
- Set financial targets for specific expense categories
- Time-based budget planning (monthly, quarterly, yearly)
- Visual progress tracking toward goals

### 🐖 Savings Goals
- Create targets for personal savings
- Monitor progress toward financial objectives
- Prioritize different savings goals
- Visual progress representation

### 📝 Reports
- Generate detailed financial reports by time period
- Customizable date ranges for report generation
- Visualize income vs expenses across time periods
- Break down spending by category with percentage analysis
- Printable report formats

## 🛠️ Technology Stack

- **Backend**: Django 5.1
- **Frontend**: HTML5, CSS3, JavaScript, Bootstrap 5
- **Database**: SQLite (development) / PostgreSQL (production)
- **Charts**: Chart.js
- **Icons**: Font Awesome

## 🚀 Setup and Installation

1. Clone the repository
```bash
git clone <repository-url>
cd finance-tracker
```

2. Create and activate virtual environment
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies
```bash
pip install -r requirements.txt
```

4. Run migrations
```bash
python manage.py migrate
```

5. Create a superuser
```bash
python manage.py createsuperuser
```

6. Run the development server
```bash
python manage.py runserver
```

7. Access the application at http://127.0.0.1:8000/

## 📁 Project Structure

- `accounts/`: User authentication and profile management
- `dashboard/`: Main dashboard and reporting features
- `transactions/`: Transaction recording and categorization
- `templates/`: HTML templates for the application
- `static/`: CSS, JavaScript, and other static assets

## 🔮 Future Enhancements

- Google OAuth integration for seamless login
- API integration with banking services
- Email notifications for budget alerts
- Recurring transaction functionality
- Export functionality for reports (CSV, PDF)
- Dark mode theme option
- Financial forecasting based on historical data
- Multiple currency support

## 📸 Screenshots

![Dashboard Screenshot](screenshots/dashboard.png)
![Transactions Screenshot](screenshots/transactions.png)
![Reports Screenshot](screenshots/reports.png)
![Budget Goals Screenshot](screenshots/budget-goals.png)

## 📱 Responsive Design

The application is fully responsive and works seamlessly on mobile devices, tablets, and desktops.

## 🔒 Security Features

- Secure authentication with password hashing
- CSRF protection on all forms
- User-specific data isolation
- Proper session management

## 📜 License

This project is licensed under the MIT License - see the LICENSE file for details.

---

### 👨‍💻 About the Developer

This project was developed as a demonstration of full-stack development skills using Django and modern web technologies. The application follows best practices for security, user experience, and code organization.

### 🙏 Acknowledgments

- Django documentation and community
- Bootstrap team for the excellent UI framework
- Chart.js for the visualization capabilities 
