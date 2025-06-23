# Android-Studio-Project-2-Hello-World

![image](https://github.com/user-attachments/assets/ea2fdd30-292a-4dc2-82b8-130b6b8abc8b)


![image](https://github.com/user-attachments/assets/90aa61f5-f9d4-4e79-a5d7-03c9f67b91b9)


# Hello Android App

This is a basic Android application developed using **Android Studio** that displays a simple welcome message using `ConstraintLayout` and `TextView` elements.

## 📱 Preview

The application displays:

Hello
Amarjeet Kumar (21BCS10768)

markdown
Copy
Edit

Centered in the middle of the screen.

## 🛠️ Technologies Used

- Java
- XML (Android Layout)
- Android Studio
- Android Emulator (Pixel 6 Pro, API 29)
- ConstraintLayout

## 📂 Project Structure

app/
├── java/
│ └── com.example.hello/
│ └── MainActivity.java
├── res/
│ ├── layout/
│ │ └── activity_main.xml
│ └── values/
│ └── strings.xml, colors.xml, themes.xml

vbnet
Copy
Edit

## 🧾 How It Works

The UI is built using `ConstraintLayout` to center two `TextView` elements on the screen:

- `TextView 1`: Displays `"Hello"`
- `TextView 2`: Displays `"Amarjeet Kumar (21BCS10768)"`

Each TextView is centered both vertically and horizontally using constraint attributes.

### activity_main.xml (Excerpt)

```xml
<TextView
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    android:text="Hello"
    app:layout_constraintBottom_toBottomOf="parent"
    app:layout_constraintTop_toTopOf="parent"
    app:layout_constraintStart_toStartOf="parent"
    app:layout_constraintEnd_toEndOf="parent" />

<TextView
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    android:text="Amarjeet Kumar (21BCS10768)"
    app:layout_constraintBottom_toBottomOf="parent"
    app:layout_constraintTop_toTopOf="parent"
    app:layout_constraintStart_toStartOf="parent"
    app:layout_constraintEnd_toEndOf="parent"
    app:layout_constraintVertical_bias="0.55" />
🚀 Getting Started
Clone the repository.

Open the project in Android Studio.

Run the app on an emulator or physical device.

👨‍💻 Author
Amarjeet Kumar

B.Tech CSE (21BCS10768)

📄 License
This project is licensed under the MIT License - see the LICENSE file for details.

yaml
Copy
Edit

---

Let me know if you'd like to add a GitHub Actions CI/CD badge, screenshots section, or links to related projects.


