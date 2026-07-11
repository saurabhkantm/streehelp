# StreeHelp 🚨

StreeHelp is a safety application built during a hackathon to help users in emergency situations.
The idea is simple — if someone is in danger and can’t use the phone properly, the app should still be able to detect it and send alerts.

---

## What it does

* Detects keywords like "help" or "bachao" using voice
* Allows manual SOS trigger
* Has a timer-based SOS option
* Sends alert emails to emergency contacts
* Shares user location using Google Maps link
* Includes loudness detection (for scream / panic situations)
* Shows nearby risky/safe areas using heatmap
* Runs in background during SOS mode

---

## Tech Stack

* Flutter (frontend)
* Node.js + Express (backend)
* MongoDB (database)
* Nodemailer (for email alerts)
* Geolocator (for location)

---

## How it works (basic idea)

When SOS is triggered (either manually, timer, or voice), the app starts monitoring.
If it detects something suspicious (keywords or loud sound), it sends an alert along with the user’s location to the saved contacts.

---

## My Contribution

I worked mainly on the backend side of the project:

* Built the backend using Node.js and Express
* Created APIs for SOS handling and user data
* Designed the alert flow (start, update, stop)
* Handled location data and storage
* Integrated email sending using Nodemailer
* Worked with MongoDB for schema and data

---

## Future Improvements

* Live location tracking instead of static location
* Better risk detection using multiple factors
* Multilingual support
* Push notifications
* Heart rate monitoring using smartwatch

---

## Note

This is a hackathon project, so it's more of a working prototype than a production-ready app.

---

## Team

Built as part of a team project (CodeStorm).
This project was developed collaboratively during a hackathon.
Original repository : https://github.com/saurabhkantm/streehelp
