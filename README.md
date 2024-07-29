# My Uber-like app

## Backend

### Setup

1. Install the necessary Python packages:
   ```bash
   pip install -r requirements.txt
   ```

2. Run the Flask Server:
   ```bash
   python app.py
   ```

### Endpoints

- `GET /`: Home route
- `POST /api/users/register`: Create a new user
- `POST /api/auth/login`: Login user
- `POST /api/locations/update`: Update user location
- `POST /api/locations/nearby`: Find nearby users

## Android App

### Setup

1. Open the `android-app` directory in Android Studio
2. Sync the project with Gradle files
3. Run the app on an emulator or a physical device

### Features

- User registeration and login
- Update user location
- Find nearby users
