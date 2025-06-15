# Sydney Weather Nerds – Flutter Forecast App

This app powers SWN's hyper-local forecasting centre using Flutter, Meteologix API, and BoM observations.

---

## 🚀 Features
- Hyper-local suburb-level forecasts
- Health sensitivity index (pollen, mould, asthma, etc.)
- 7-day outlook with rain and emoji icons
- Hourly breakdown with “Favourite Time” tagging
- Live obs comparison (BoM) vs forecast

---

## 🛠 Project Structure

| Folder           | Purpose                                  |
|------------------|------------------------------------------|
| `lib/`           | Flutter Dart app code                    |
| `assets/icons/`  | Forecast & health icon assets            |
| `assets/fonts/`  | (Optional) Custom fonts                  |
| `data/mock/`     | Example forecast JSON for local testing  |
| `web/`           | Flutter Web PWA scaffold (index.html)   |

---

## 🧪 Local Development

```bash
git clone https://github.com/SydneyWeatherNerds/flutter_swn_app.git
cd flutter_swn_app
flutter pub get
flutter run
```

Ensure you’ve set up:
- Flutter SDK (3.10+ recommended)
- Android Studio / VS Code (with Dart/Flutter plugins)

---

## 📦 Coming Soon

- GitHub Pages asset hosting
- Web app deployment
- GitHub Actions for CI/CD builds
- Themed layouts + health alert automation
