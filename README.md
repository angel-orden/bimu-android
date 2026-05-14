# BIMU Android

Android client for BIMU, a client-server application focused on cycling route management and group outings.

## Description

BIMU Android is the mobile client of the BIMU platform. The application allows users to search and manage cycling routes, interact with social features and participate in group outings through a REST backend API.

The project was designed following a client-server architecture, connecting the Android application with a backend service responsible for user management, routes, outings and persistence using MongoDB Atlas.

## Technologies

* Kotlin
* Android Studio
* Retrofit
* REST APIs
* OSMDroid
* MongoDB-backed API
* Material Design Components

## Main Features

* User profile management
* Cycling route creation and visualization
* Route filtering by difficulty and distance
* Map-based functionality using OSMDroid
* Group outing management
* Social features and achievements
* Connection with backend REST API

## Architecture

Android App → Retrofit Client → REST API → MongoDB Atlas

## Related Repositories

* Backend API: [https://github.com/angel-orden/bimu-backend](https://github.com/angel-orden/bimu-backend)

## Local Setup

### Clone repository

```bash
git clone https://github.com/angel-orden/bimu-android.git
```

### Open project

Open the project using Android Studio.

### Configure backend URL

Set the backend API URL in the Retrofit configuration file.

Example:

```kotlin
const val BASE_URL = "https://your-backend-url.com/"
```

### Run application

Use Android Studio to run the application on an emulator or Android device.

## Project Goals

* Develop a complete client-server Android application
* Integrate Android with a REST backend architecture
* Implement route filtering and map-based functionality
* Improve API communication and mobile architecture
* Build a real-world full-stack project

## Author

Ángel Orden Rodríguez

* GitHub: [https://github.com/angel-orden](https://github.com/angel-orden)
* LinkedIn: [https://linkedin.com/in/ángel-orden-rodriguez](https://linkedin.com/in/ángel-orden-rodriguez)
