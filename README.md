# GESTIME
CONTROL YOUR WORKING HOURS 
Time Tracking Bot with Telegram 🤖
This project is a Telegram bot designed to manage time tracking (clock-in and clock-out) using the user's location to record data. The bot allows users to log their working hours, generate daily and monthly reports, and check their current status.

Key Features 🚀
Clock-In and Clock-Out: Users can log their clock-in and clock-out times using an interactive menu.

Geolocation: The bot requests the user's location to accurately record time entries.

Daily and Monthly Reports: Users can generate reports of their working hours.

Current Status: Check the last recorded time entry and if there are any pending entries.

SQLite Database: Stores all information in a local database.

Requirements 📋
Python 3.8 or higher

Required libraries: python-telegram-bot, geocoder, sqlite3

Installation 🛠️
Clone the repository:

bash
Copy
git clone https://github.com/yourusername/yourrepository.git
cd yourrepository
Install dependencies:

bash
Copy
pip install -r requirements.txt
Configure the bot:

Create a bot on Telegram using BotFather and obtain the token.

Replace the token in the code:

python
Copy
application = Application.builder().token('YOUR_TOKEN_HERE').build()
Start the bot:

bash
Copy
python tiempo.py
Using the Bot 🤖
Start the bot: Send /start to begin.

Clock-In/Clock-Out: Use the "📍 Clock-In" or "🚪 Clock-Out" buttons to log your time.

Share Location: The bot will ask you to share your location to complete the time entry.

Reports: Use the "📊 Daily Report" or "📅 Monthly Report" buttons to get reports of your working hours.

Current Status: Use the "📋 Current Status" button to check your last time entry.

Project Structure 📂
tiempo.py: Contains the main logic of the bot, including command and message handlers.

DatabaseManager: Class to manage the SQLite database connection.

init_db(): Function to initialize the database and create necessary tables.

obtener_detalles_ubicacion(): Function to get location details using reverse geocoding.

Contributions 🤝
Contributions are welcome! If you want to improve the project, follow these steps:

Fork the repository.

Create a new branch (git checkout -b feature/new-feature).

Make your changes and commit them (git commit -am 'Add new feature').

Push to the branch (git push origin feature/new-feature).

Open a Pull Request.

License 📄
This project is licensed under the MIT License. See the LICENSE file for more details.

Contact 📧
If you have any questions or suggestions, feel free to contact me:

Email: youremail@example.com

Telegram: @kikelamort

Thank you for using this bot! I hope it helps you manage your time tracking efficiently. 😊
