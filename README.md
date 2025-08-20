# Timesheet App

A mobile-friendly web-based timesheet submission app built with Flask. Designed for staff to submit weekly timesheets and for admins to manage approvals and exports.

## 🚀 Features
- User authentication (login/logout)
- Weekly timesheet submission
- Admin dashboard for approvals
- CSV export of timesheets
- Mobile-responsive design

## 🛠 Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/timesheet-app.git
   cd timesheet-app
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the app:
   ```bash
   python app.py
   ```

## 🌐 Deployment on Render
1. Push your code to GitHub.
2. Add `requirements.txt` and `render.yaml` to the root directory.
3. Go to [https://render.com](https://render.com) and create a new Web Service.
4. Connect your GitHub repo and set the start command to:
   ```bash
   python app.py
   ```

## 📄 License
This project is open-source and available under the MIT License.
