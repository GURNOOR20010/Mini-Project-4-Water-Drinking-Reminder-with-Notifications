# Mini-Project-4-Water-Drinking-Reminder-with-Notifications
# 💧 Water Drinking Reminder

A simple Python desktop application that reminds users to drink water at regular intervals using desktop notifications. This project helps maintain healthy hydration habits by sending automatic reminders based on a user-defined time interval.

## 📌 Features

- ⏰ Sends desktop notifications at regular intervals.
- 💧 Helps users stay hydrated throughout the day.
- ⚙️ Easy to customize the reminder interval.
- 🖥️ Lightweight and beginner-friendly Python project.
- 🚀 Uses the Plyer library for cross-platform desktop notifications.

## 🛠️ Technologies Used

- Python
- Plyer
- Time Module

## 📁 Project Structure

```text
Water-Drinking-Reminder/
│── water_reminder.py
│── README.md
```

## 📦 Installation

1. Clone the repository.

```bash
git clone https://github.com/your-username/Water-Drinking-Reminder.git
```

2. Navigate to the project directory.

```bash
cd Water-Drinking-Reminder
```

3. Install the required library.

```bash
pip install plyer
```

## ▶️ Usage

Run the Python script:

```bash
python water_reminder.py
```

The application will start and display:

```text
Water Drinking Reminder Started
You will get a notification every 30 minutes
```

## ⚙️ Customize Reminder Interval

The reminder interval is set in the following line:

```python
water_reminder(30)
```

Examples:

```python
water_reminder(1)      # Reminder every 1 minute
water_reminder(15)     # Reminder every 15 minutes
water_reminder(30)     # Reminder every 30 minutes
water_reminder(60)     # Reminder every 60 minutes
```

For testing purposes:

```python
water_reminder(0.1)
```

This sends a notification approximately every **6 seconds**.

## 📸 Notification

**Title**

```
Drink Water
```

**Message**

```
Time to drink water and stay hydrated.
```

## 🚀 Future Improvements

- Add a graphical user interface (GUI).
- Include notification sounds.
- Allow users to start, pause, and stop reminders.
- Track daily water intake.
- Add customizable notification messages.
- Package the application as a desktop executable.

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repository, make improvements, and submit a pull request.

## 📄 License

This project is licensed under the MIT License.

---

**Developed by Gurnoor Singh**
