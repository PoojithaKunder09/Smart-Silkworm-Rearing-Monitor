# Reshme-Namma Pride 🐛
## Silkworm Rearing Monitor - Android App

**MindMatrix VTU Internship Program | Project Title: 52**

---

## 🚀 How to Open in Android Studio

1. **Unzip** this folder
2. Open **Android Studio**
3. Click **"Open"** → Select the `ReshmeNammaPride` folder
4. Wait for **Gradle Sync** to complete (may take 2-5 minutes first time)
5. Connect an **Android device** or start an **emulator** (API 24+)
6. Click the **▶ Run** button

---

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

## 🗂️ Project Structure

```
app/src/main/java/com/reshmenammapride/
├── activities/
│   ├── SplashActivity.kt
│   ├── HomeActivity.kt
│   ├── AddBatchActivity.kt
│   ├── MonitoringActivity.kt
│   └── HistoryActivity.kt
├── database/
│   ├── AppDatabase.kt
│   ├── BatchDao.kt
│   └── ClimateRecordDao.kt
├── models/
│   ├── Batch.kt
│   └── ClimateRecord.kt
├── adapters/
│   └── HistoryAdapter.kt
├── utils/
│   └── SmartAdviceEngine.kt
└── notifications/
    └── NotificationHelper.kt
```

---

## 🎓 Viva Points

1. **Why silkworms are temperature sensitive** - A 2°C change can kill an entire batch
2. **Why humidity matters** - Low humidity dries out silkworms; high humidity causes fungal disease
3. **Instar stages** - 5 larval stages with different ideal conditions
4. **Smart agriculture** - Using mobile tech to monitor and alert farmers
5. **Room Database** - Stores batch and climate history locally
6. **Coroutines** - Non-blocking async operations for DB access
7. **LiveData** - Reactive UI that auto-updates when data changes

---

## 👨‍💻 Tech Stack
- **Language**: Kotlin
- **Database**: Room (SQLite)
- **UI**: Material Design Components
- **Architecture**: MVVM-lite with LiveData
- **Min SDK**: 24 (Android 7.0)
- **Target SDK**: 34 (Android 14)
