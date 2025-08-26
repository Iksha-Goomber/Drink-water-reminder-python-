# Drink-water-reminder-python-
# The Drink Water Reminder is a lightweight Python project that runs in the background and sends alerts at set intervals, helping users stay hydrated. It demonstrates how simple Python scripts can solve real-life problems in a practical and beginner-friendly way.
import time
from plyer import notification

while True:
    print("Time to drink water!")
    notification.notify(title="Time to drink water!", message="You need to drink some water")
    time.sleep(60*60)
