# Python-projects-import datetime

# Get the current time
current_time = datetime.datetime.now()
hour = current_time.hour

# Define greetings based on the time of day
if 5 <= hour < 12:
    greeting = "Good morning!"
elif 12 <= hour < 17:
    greeting = "Good afternoon!"
elif 17 <= hour < 20:
    greeting = "Good evening!"
else:
    greeting = "Good night!"

# Display the greeting
print(greeting)
