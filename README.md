# -Alarm-Clock-Python-Tkinter-
⏰This project is a GUI-based Alarm Clock built with Python and Tkinter. It allows users to set alarms, snooze them, and repeat them daily. It also features a live digital clock display and cross-platform sound notifications.

<img width="428" height="313" alt="Screenshot 2025-08-25 153158" src="https://github.com/user-attachments/assets/a3312d5e-0ffb-442f-acc1-3bb965f4eb61" />


⏰ Alarm Clock – Python (Tkinter)
📖 Overview

This project is a GUI-based Alarm Clock built with Python and Tkinter.
It allows users to set alarms, snooze them, and repeat them daily. It also features a live digital clock display and cross-platform sound notifications.

🚀 Features

🕒 Digital Clock with real-time updates.

⏰ Set Alarms (with AM/PM format).

🔁 Repeat Daily option.

🔕 Stop Alarm button.

😴 Snooze Alarm (adds 5 minutes).

🎶 Sound Alert with cross-platform support:

Windows → winsound.Beep() (multi-tone).

Others → Tkinter bell().

🖼️ User-friendly GUI built with Tkinter.

📂 Project Structure

alarm_clock.py → Main script with GUI and alarm logic.

▶️ Run the Project
1️⃣ Install Python dependencies (Tkinter comes pre-installed)
# For Windows beep support
pip install pywin32


(Tkinter and datetime are included in Python standard library.)

2️⃣ Run the script
python alarm_clock.py

⚙️ How It Works

Launch the app → Digital clock is shown.

Enter alarm time (e.g., 07:30) and select AM/PM.

Click Set Alarm → Status shows scheduled alarm.

At the alarm time → popup + sound alert.

Options:

Stop → Dismiss alarm.

Snooze 5 min → Delay alarm.

Repeat daily → Alarm auto-resets for next day.

🖼️ GUI Preview

Main Window: Digital clock + alarm input fields.

Popup Alert: “⏰ Time’s up!” with sound.

🔮 Future Enhancements

🎵 Custom alarm tones (MP3/WAV).

🌓 Dark/Light theme support.

📱 Export as standalone desktop app (.exe / .dmg).

⏳ Countdown Timer feature.
