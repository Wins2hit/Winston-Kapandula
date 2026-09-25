# SimpleJavaFXApp

A minimal JavaFX desktop app built for Mulungushi University's JavaFX Lab 1.
Shows a window with a label and a button; clicking the button updates the label text.

## Requirements
- JDK 21
- Gradle 9.7.1+ (or use the Gradle wrapper if added)

## Run
```bash
gradle run
```

## Project structure
```
SimpleJavaFXApp/
├── build.gradle
└── src/main/java/
    ├── module-info.java
    └── com/example/hellofx/
        ├── HelloJavaFX.java   # JavaFX UI + logic
        └── Main.java          # Launcher
```

## Push to GitHub
```bash
git init
git add .
git commit -m "First JavaFX Lab Complete"
git branch -M main
git remote add origin <your-repo-url>
git push -u origin main
```
