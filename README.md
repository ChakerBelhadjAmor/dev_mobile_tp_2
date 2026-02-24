# Hello Toast 

A simple Android application built as part of a mobile development lab at ENICARTHAGE (2025/2026). The app demonstrates basic interactive UI concepts using Android's `ConstraintLayout`, `Button`, `TextView`, and Toast messages.

##  Features

- **Toast Button** – Displays a short Toast message ("Hello Toast!") when tapped.
- **Count Button** – Increments and displays a click counter in a `TextView`.

##  Built With

- **Language:** Java
- **Min SDK:** API 24 (Android 7.0 Nougat)
- **Layout:** ConstraintLayout
- **IDE:** Android Studio (Giraffe)

##  Project Structure

```
app/
├── src/
│   └── main/
│       ├── java/com/example/hellotoast/
│       │   └── MainActivity.java       # Main activity with button handlers
│       └── res/
│           ├── layout/
│           │   └── activity_main.xml   # UI layout with ConstraintLayout
│           └── values/
│               ├── strings.xml         # String resources
│               └── colors.xml          # Color resources
```

##  Getting Started

### Prerequisites

- Android Studio installed
- Android emulator or physical device running API 24+

### Running the App

1. Clone the repository:
   ```bash
   git clone https://github.com/ChakerBelhadjAmor/dev_mobile_tp_2.git
   ```
2. Open the project in Android Studio.
3. Run the app via **Run > Run 'app'** or click the ▶️ toolbar button.

##  UI Overview

The layout consists of three elements stacked vertically:

| Element | ID | Description |
|---|---|---|
| Button | `button_toast` | Shows a Toast message on click |
| TextView | `show_count` | Displays the current click count |
| Button | `button_count` | Increments the counter on click |

All elements use `match_constraint` for width and are constrained with 8dp margins.

##  Styling

- **Primary color:** `#FF410081` (deep purple)
- **Button text:** White
- **Counter background:** `#FFFF00` (yellow)
- **Counter text size:** 160sp, Bold, centered

##  Concepts Covered

- Using the Android Studio Layout Editor (Design + Blueprint views)
- Working with `ConstraintLayout` and constraint handles
- Setting view attributes (`layout_width`, `layout_height`, `match_constraint`, `wrap_content`)
- Extracting string resources to `strings.xml`
- Adding `onClick` handlers via XML (`android:onClick`)
- Displaying a `Toast` message
- Updating a `TextView` from Java using `findViewById` and `setText`

## 🔗 Reference

Lab based on the [ENETCOM Android Codelabs](https://codelabs-enetcom.khammami.tn/codelabs/interface-utilisateurinteractive/index.html).
