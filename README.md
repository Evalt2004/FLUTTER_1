# FLUTTER_1


Invoke-WebRequest "https://github.com/Evalt2004/FLUTTER_1/raw/main/flutter_exp6.zip" -OutFile "flutter_exp6.zip"

flutter doctor -v
flutter devices


flutter emulators

# Launch an emulator (use the id printed, no angle brackets)
flutter emulators --launch Pixel_Fold_API_36
# then check devices

flutter devices

________________________________________
EXP 1 — Simple App (Hello / basic UI)
cd C:\Users\ADMIN\Desktop\FLUTTER
flutter create flutter_exp1
cd flutter_exp1
code .    # open VS Code and replace lib/main.dart with your Exp1 code
flutter pub get
flutter run -d chrome
Show: App starts in Chrome and UI elements appear.
Fallback: flutter run -d edge if you prefer Edge.
________________________________________
EXP 2 — Layouts (Container/Row/Column)
cd C:\Users\ADMIN\Desktop\FLUTTER
flutter create flutter_exp2
cd flutter_exp2
code .
# paste Exp2 code into lib/main.dart
flutter pub get
flutter run -d chrome
Show: Layout renders properly (containers, rows, columns).



EXP 3 — Stateful Widget / Counter or Form
cd C:\Users\ADMIN\Desktop\FLUTTER
flutter create flutter_exp3
cd flutter_exp3
code .
# paste Exp3 code (stateful widget) into lib/main.dart
flutter pub get
flutter run -d chrome
Show: Interactivity works (button increments, state persists while app runs).
________________________________________
EXP 4 — Navigation & Routes
cd C:\Users\ADMIN\Desktop\FLUTTER
flutter create flutter_exp4
cd flutter_exp4
code .
# paste Exp4 code with routes into lib/main.dart (and other files if needed)
flutter pub get
flutter run -d chrome
Show: Navigate between screens, back stack works.



EXP 5 — Form Validation / Input Handling
cd C:\Users\ADMIN\Desktop\FLUTTER
flutter create flutter_exp5
cd flutter_exp5
code .
# paste Exp5 form code into lib/main.dart
flutter pub get
flutter run -d chrome
Show: Validation messages appear, valid submission accepted.


EXP 6 — SQLite Product Inventory Tracker (Android target preferred)
This one uses sqflite. If emulator is healthy, run on emulator. If emulator is down, you can demo web fallback (we already prepared a web fallback main.dart earlier).
Commands:
cd C:\Users\ADMIN\Desktop\FLUTTER
flutter create flutter_exp6
cd flutter_exp6
code .
# paste the project files:
#   lib/main.dart        (use the web-safe main.dart we gave, or original for Android)
#   lib/product.dart
#   lib/database_helper.dart
# then add sqflite deps:
flutter pub add sqflite
flutter pub add path
flutter pub add path_provider
flutter pub get

# start emulator (use the id you have: Medium_Phone_API_36 or Pixel_Fold_API_36)
flutter emulators --launch Pixel_Fold_API_36
# confirm device present
flutter devices
# run app on the emulator
flutter run



flutter emulators
 --launch Pixel_Fold_API_36_2

flutter run -d Pixel_Fold_API_36_2

flutter run -d edge


