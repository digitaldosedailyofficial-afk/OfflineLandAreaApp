# OfflineLandAreaApp

Offline Android app to estimate land area by walking the perimeter. **No GPS, no internet** — uses step + heading dead-reckoning (inertial) so accuracy is limited and drifts over distance.

## How it works
1. Enter your stride length in meters (default 0.75).
2. Press **Start** and walk the boundary (one full loop).
3. Press **Stop** to compute area (Shoelace formula).
4. Units shown: Square meters, Square feet, Guntha (1 acre = 40 guntha), Acres, Hectares.

## Improving Accuracy
- Calibrate your stride: measure a known distance (e.g., 20 m), walk it, divide distance by steps.
- Walk steady, keep phone orientation consistent.
- For better estimate, make two laps and stop—future enhancement could average multi-lap track.

## Build
Open in Android Studio, let Gradle sync, then Build > Build APK(s).

## Disclaimer
Dead-reckoning accumulates error. Use results as rough estimates only. For precise/official survey, use professional equipment.
