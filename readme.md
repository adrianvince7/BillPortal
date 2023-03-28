#BillPortal

BillPortal is a web application for managing bills, specifically designed for households or small businesses. This project is built using Python, Django and Bootstrap.

##Features

User registration and authentication with token to mitigate the risk of fraud.
 TODO: integrate SendGrid SMTP email service

Role-based access control
Add, edit, and delete bills
Filter and search bills by date, amount, and status
Generate and download bills in PDF format
View statistics and reports on bills

##Installation

Clone the repository using git clone https://github.com/your-username/your-project.git.
Install the required dependencies using pip install -r requirements.txt.
Set up a PostgreSQL database and configure the application to connect to it. The database configuration can be found in the settings.py file.
Run the Django server using the command python manage.py runserver.

##Usage

*Open a web browser and navigate to http://127.0.0.1:8000.
*Register for an account or log in with an existing account.
*Add bills using the "Add Bill" button on the main dashboard.
*Edit or delete bills using the corresponding buttons on the main dashboard.
*Filter and search bills using the options provided on the main dashboard.
*Generate PDF bills using the "Download PDF" button on the main dashboard.
*View statistics and reports using the "Statistics" and "Reports" links on the navigation bar.

#Contributing

Contributions are welcome! To contribute to this project, please fork the repository, make your changes, and submit a pull request.

Credits

This project was created by Adrian Vince.

License

This project is licensed under the MIT License. See the LICENSE file for more information.