🏛️ Virtue Tracker

A personal virtue tracking app built with Python and Tkinter, inspired by Roman values and Benjamin Franklin's method of self-improvement. Users can rate themselves daily on a wide range of virtues, provide justifications, and visualize progress across time.
📸 Features

    ✅ Daily self-assessment of Roman virtues

    📝 Space to justify each rating

    💾 Saves logs to local files

    📊 Monthly graph visualizations

    📂 View past entries via an interactive date selector

    📅 Inspired by Benjamin Franklin's method of tracking and improving personal virtues

🧰 Requirements

    Python 3.8+

    Libraries:

        pandas

        matplotlib

        tkinter (comes with Python)

Install dependencies:

pip install pandas matplotlib

🚀 Running the App

    Clone this repo:

git clone https://github.com/yourusername/virtue-tracker.git
cd virtue-tracker

    Run the application:

python virtutes.py

🧪 How It Works
🌿 Rate Virtues

Scroll through a long list of Roman virtues and rate each one from 1 (low) to 5 (high), adding optional justifications. This is inspired by Benjamin Franklin's method, where Franklin tracked 13 virtues and worked on improving them systematically.

💾 Save Data

Click "Save Data" to store your entries. It will save:

    A CSV file: virtues_YYYY-MM-DD.csv

    A text file for notes: justifications_YYYY-MM-DD.txt

These are saved to:
📁 ~/Desktop/VirtueLogs/
📈 Show Monthly Statistics

Click "Show Monthly Statistics" to plot a line graph showing your progress for each virtue over the current month.
📂 Open Memoire

Click "Open Memoire" to choose a saved day and view both your virtue scores and written justifications from that date.
📁 File Structure

virtutes.py            # Main app file
VirtueLogs/            # Folder (auto-created) where daily logs are saved
  ├── virtues_YYYY-MM-DD.csv
  └── justifications_YYYY-MM-DD.txt

📚 Virtues Included

The app tracks 40+ Roman virtues, such as:

    Gravitas – Responsibility and seriousness

    Industria – Hard work

    Pietas – Respect for natural order

    Virtus – Moral excellence and courage

Full descriptions are visible in the app interface.
💡 Potential Improvements

    Export to PDF

    Dark mode UI

    Cloud sync

    Aggregated dashboards by week/month/year

🛡️ License

This project is open source and uses the MIT License.
