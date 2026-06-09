# Reshme-Namma Pride 🐛
## Silkworm Rearing Monitor - Android App

## 📱 App Features

### ✅ Implemented
- **Splash Screen** - Animated logo with Kannada tagline
- **Home Screen** - Dashboard with batch count & navigation
- **Add Batch** - Create silkworm batches with breed, date, instar
- **Climate Monitor** - Enter temp/humidity, get smart advice
- **Smart Advice Engine** - Instar-specific logic (5 stages)
- **Color Status Indicator** - 🟢 Safe / 🟠 Caution / 🔴 Danger
- **Line Chart** - Temperature & humidity history graph
- **Room Database** - Persistent storage of all records
- **History Screen** - View all past climate records
- **Notifications** - Push alerts for dangerous conditions

---

## 🌡️ Instar Stage Ideal Conditions

| Instar | Temp (°C) | Humidity (%) |
|--------|-----------|--------------|
| 1      | 28-30     | 85           |
| 2      | 27-29     | 80           |
| 3      | 26-28     | 75           |
| 4      | 25-27     | 70           |
| 5      | 24-26     | 65           |

---

## 📦 Libraries Used

- **MPAndroidChart** - Line graphs for temp/humidity
- **Room Database** - Local data persistence
- **Material Components** - UI components
- **Kotlin Coroutines** - Async database operations
- **LiveData** - Reactive UI updates

---


## 👨‍💻 Tech Stack
- **Language**: Kotlin
- **Database**: Room (SQLite)
- **UI**: Material Design Components
- **Architecture**: MVVM-lite with LiveData
- **Min SDK**: 24 (Android 7.0)
- **Target SDK**: 34 (Android 14)
