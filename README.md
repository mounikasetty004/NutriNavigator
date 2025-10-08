# 🥗 NutriNavigator – AI-Powered Nutrition & Fitness Assistant

NutriNavigator is an **AI-powered web application** that provides **personalized meal, restaurant, and workout recommendations** based on user input such as age, gender, weight, height, allergies, diseases, and region.
Built with **Flask (Python)** and **Tailwind CSS**, it features a **modern responsive interface** and integrates **Groq LLaMA 3.3** for natural language–based recommendations.

---

## 🚀 Features

* 🤖 **AI-driven Recommendations** – Uses LLaMA 3.3 (via Groq) to generate meal, restaurant, and workout plans.
* 🍛 **Personalized Diet Plans** – Suggests food according to user preferences, allergies, and health conditions.
* 💪 **Workout Suggestions** – Offers custom exercises based on user body metrics and fitness level.
* 🍴 **Nearby Restaurant Suggestions** – AI recommends healthy restaurants and dishes.
* 🌍 **Region-Aware Food Suggestions** – Suggests local and culturally familiar meals.
* 📱 **Fully Responsive UI** – Optimized for both mobile and desktop using Tailwind CSS.
* ⚙️ **Lightweight, No Database Needed** – AI dynamically generates recommendations without storing data.

---

## 🧠 Tech Stack

| Category        | Technology Used                       |
| --------------- | ------------------------------------- |
| Frontend        | HTML, Tailwind CSS                    |
| Backend         | Flask (Python)                        |
| AI Model        | LLaMA 3.3 via Groq API                |
| Template Engine | Jinja2                                |
| Deployment      | Localhost / Any Flask-compatible host |

---

## 📂 Project Structure

```
NutriNavigator/
│
├── app.py                      # Main Flask app
├── templates/
│   ├── index.html              # Home page with form
│   ├── about.html              # About page
│   ├── services.html           # Services page
│   ├── contact.html            # Contact page
│   ├── recommend.html          # AI recommendation output
│
├── static/
│   ├── css/
│   │   └── style.css           # Custom styles (optional)
│   └── images/                 # App images, icons
│
├── myenv/                      # Virtual environment (optional)
└── requirements.txt            # Project dependencies
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/NutriNavigator.git
cd NutriNavigator
```

### 2️⃣ Create & Activate Virtual Environment

```bash
python -m venv myenv
myenv\Scripts\activate   # On Windows
source myenv/bin/activate  # On macOS/Linux
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Run the Application

```bash
python app.py
```

Then open your browser and go to 👉 **[http://127.0.0.1:5000](http://127.0.0.1:5000)**

---

## 🧾 Example User Inputs

| Field      | Example     |
| ---------- | ----------- |
| Name       | Mounika     |
| Age        | 22          |
| Gender     | Female      |
| Height     | 160 cm      |
| Weight     | 55 kg       |
| Allergies  | Dairy       |
| Diseases   | None        |
| Region     | South India |
| Preference | Vegetarian  |

---

## 🧩 Example AI Output

**NutriNavigator Recommendation:**

* 🥗 *Breakfast:* Idli with sambar, fruit smoothie
* 🍛 *Lunch:* Brown rice with dal, stir-fried veggies
* 🌙 *Dinner:* Grilled paneer with soup
* 🏋️ *Workout:* 30 mins yoga, 20 mins light cardio
* 🍴 *Restaurant:* Sattvam Healthy Kitchen (Bangalore)

---

## 💡 Why NutriNavigator?

* Combines **diet, workout, and restaurant suggestions** in one platform.
* Considers **regional, allergy, and disease-specific** factors.
* Generates **dynamic, AI-powered recommendations**—no static database required.
* Built with **clean UI and responsive design** for a seamless experience.

---

## 🌟 Future Enhancements

* 📊 User dashboards with progress tracking
* 🔒 Authentication & user profiles
* 📱 Mobile app version (React Native or Flutter)
* 🧬 Integration with wearable health devices (Fitbit, Apple Watch)
* 🗣️ Voice-based nutrition assistant

---

## 👩‍💻 Author

**Developed by:** Neelisetty Mounika
📧 *Email:* [[your-email@example.com](mailto:your-email@example.com)]
🌐 *GitHub:* [https://github.com/your-username](https://github.com/your-username)

---

## 🪪 License

This project is licensed under the **MIT License** – free to use, modify, and distribute.

---

### 🥇 *“Eat smart, stay fit — NutriNavigator guides you every bite and step of the way.”*

