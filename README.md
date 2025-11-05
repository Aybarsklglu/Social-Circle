SocialCircle
SocialCircle is a Python-based sports networking application designed to bring people together through real-life sports activities.
Instead of passive scrolling, SocialCircle focuses on action: join events, create your own sports activities, discover people who like the same sports as you — and meet up in person.
Key Features
User account creation & login
Users select which sports categories they are interested in (13 categories total)
Lists upcoming sports events based on user interests
Create your own event:
event name
date and end date
time and end time
sport category
city (all 81 cities of Türkiye)
notes field
Dynamic filtering: filter events by category or by city
Prevents creating events in the past
Prevents event conflicts and invalid dates
SQLite database storage for users & events
Tech Stack
Component	Technology
Language	Python
GUI	Tkinter
Databases	SQLite (kullanicilar2.sqlite + etkinlikler3.sqlite)
Images / UI assets	Pillow (PIL)
Calendar widgets	tkcalendar
How It Works
New users register and choose the sports they like.
After login, users see upcoming events that match their selected sports.
Users can create new sport events with full validation (time, date, category, etc.).
Users can filter the event list by Category or by City manually.
Purpose & Vision
The goal of SocialCircle is to connect strangers through sports — not dating, not passive chat — but real activity, movement and human connection.
Sports are one of the easiest ways to meet new people in a healthy way.
Author
Developed by: Aybars Kuloğlu
