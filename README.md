# Password Manager

By: Brandon Wise

A full-stack password manager web app. Users can securely store their credentials in Firebase Firestore and log in from any device with Firebase Authentication.

## Tech stack

- Python, Flask (backend)
- HTML, CSS, JavaScript (frontend)
- Firebase Firestore (credential storage)
- Firebase Authentication (cross-device login)

## Project structure

- `main/` — Flask application
- `public/` — frontend assets
- `firebase.json` — Firebase Hosting configuration

## Setup

1. Clone the repository
2. Install the Python dependencies used by the Flask app
3. Place your Firebase service account key as `key.json` inside `main/` (this file is intentionally not committed — never share it)
4. Point the Firebase configuration at your own Firebase project
5. Run the Flask app and open the frontend

## Security notes

- `key.json` (service account credentials) is referenced by the app but excluded from version control. If you fork this repo, generate your own key in the Firebase console.
