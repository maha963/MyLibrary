# MyLibrary
A simple Android library for displaying toast messages.

---

## Features
- method for showing toast messages.

---

## How to Use

### 1. Download the `.aar` File
Download the `mylibrary-debug.aar` file from this repository.

### 2. Add the `.aar` File to Your Project
1. Place the `.aar` file in your project under `app/libs`.
2. Update your `app/build.gradle` file:
  
   dependencies {
       implementation(files("libs/mylibrary-debug.aar"))
   }

### 3. Import the ToastHelper class
