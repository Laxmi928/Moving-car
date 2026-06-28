# 🚗 Moving Car Animation

A simple yet visually engaging **Moving Car Animation** built using **HTML**, **CSS**, and **JavaScript**. This project simulates a moving car by animating the road, rotating the wheels, adding realistic shaking effects, and playing a looping engine sound to create an immersive driving experience.

---

## 📖 About the Project

This project demonstrates the use of **CSS keyframe animations** and **JavaScript audio handling** to create a realistic car-driving animation. The car appears to move forward while the animated road, rotating wheels, and subtle camera shake enhance the visual experience.

---

## ✨ Features

* 🚘 Animated moving car
* 🛣️ Infinite scrolling road animation
* 🛞 Rotating car wheels
* 🌳 Layered background with sky and trees
* 📳 Realistic car suspension (bounce) effect
* 🎥 Camera/body shake animation
* 🔊 Looping engine sound effect
* 📱 Full-screen responsive layout
* 🎨 Lightweight and beginner-friendly project

---

## 🛠️ Technologies Used

* **HTML5** – Structure of the webpage
* **CSS3** – Styling and animations
* **JavaScript** – Engine sound functionality

---

## 📂 Project Structure

```text
Moving-Car-Animation/
│── index.html
│── style.css
│── script.js
│── background.jpg
│── trees.png
│── track.png
│── car_body.png
│── car_wheel_left.png
│── car_wheel_right.png
│── sound.mp3
└── README.md
```

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/moving-car-animation.git
```

### 2. Navigate to the project folder

```bash
cd moving-car-animation
```

### 3. Run the project

Simply open **index.html** in your browser.

For a better development experience, use the **Live Server** extension in Visual Studio Code.

---

## ⚙️ Animations Used

| Animation       | Purpose                                         |
| --------------- | ----------------------------------------------- |
| `wheelRotation` | Rotates both wheels continuously                |
| `carMove`       | Moves the road to simulate driving              |
| `shake`         | Creates a realistic bouncing effect for the car |
| `shakebody`     | Adds a camera shake effect for immersion        |

---

## 🎵 JavaScript Functionality

The JavaScript file creates an audio element dynamically, loads an engine sound, enables looping, and plays it throughout the animation.

```javascript
var audio = document.createElement('audio');
audio.setAttribute('src', 'sound.mp3');
audio.loop = true;
audio.play();
```

> **Note:** Some browsers block autoplay with sound until the user interacts with the page. Click anywhere on the page if the audio does not start automatically.

---

## 📸 Preview

Add a screenshot or GIF of your project here.

```text
preview.gif
```

or

```text
screenshot.png
```

---

## 💡 How It Works

* The **road** continuously scrolls from right to left to create the illusion of movement.
* The **car** remains fixed while the moving background simulates forward motion.
* Both **wheels rotate** using CSS keyframe animations.
* The **car body bounces** slightly to imitate suspension movement.
* The **camera shake** effect enhances the realism of the animation.
* JavaScript plays a looping engine sound for a more immersive driving experience.

---

## 🔮 Future Enhancements

* 🌙 Day and Night mode
* 🌧️ Rain and weather effects
* ☁️ Animated clouds
* 🚦 Traffic lights
* 🚗 Multiple moving vehicles
* ⌨️ Keyboard controls for acceleration and braking
* 🔊 Speed-based engine sound
* 📱 Improved mobile responsiveness

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository.
2. Create a feature branch.
3. Commit your changes.
4. Push to your branch.
5. Open a Pull Request.

---

## 👩‍💻 Author

**Laxmi Singh**

---

## ⭐ Support

If you found this project helpful or interesting, please consider giving it a **⭐ Star** on GitHub. It helps others discover the project and motivates further improvements.
