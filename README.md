# 🤖 Hand Gesture-Based Math Solver using OpenCV & MediaPipe

This project is a **hand gesture-controlled math solver** built with Python, OpenCV, and MediaPipe. It uses your webcam to recognize real-time hand gestures and interprets them as mathematical operations and numbers, allowing you to calculate expressions with just your fingers — no mouse or keyboard required!

## 🔍 Features

- ✌️ Detects hand gestures using **MediaPipe** and **OpenCV**
- ➕ Supports basic arithmetic: `+`, `-`, `*`, `/`
- 🧮 Finger counting to input numbers from `0` to `5`
- 🖐 Combines gestures from **both hands** to detect complex operations
- 🧼 Gestures for clear, delete, evaluate (`=`), and even exit the program

---

## 🛠️ Tech Stack

- **Python 3**
- **OpenCV**
- **MediaPipe**
- **NumPy**

---

## 🚀 How It Works

| Gesture | Function |
|--------|----------|
| One finger on each hand | `+` |
| 1️⃣ + 2️⃣ fingers | `-` |
| 1️⃣ + 3️⃣ fingers | `*` |
| 1️⃣ + 4️⃣ fingers | `/` |
| 2️⃣ + 2️⃣ fingers | `del` |
| 0️⃣ fingers on both hands | `=` |
| 5️⃣ fingers on both hands | `clear` |
| 1️⃣ finger on each hand & bring fingertips together | `exit` |
| Show 1-5 fingers on one hand | Enters that number into expression |

---

## 💻 Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/dhxrun1/gesture-math-solver.git
cd gesture-math-solver
2. Install Dependencies
Make sure you have Python 3 installed, then run:

bash
Copy
Edit
pip install -r requirements.txt
3. Run the App
bash
Copy
Edit
python main.py
Make sure your webcam is enabled.

📂 File Structure
bash
Copy
Edit
gesture-math-solver/
├── main.py            # Main Python file (gesture detection logic)
├── README.md          # You're reading it!
└── requirements.txt   # Python dependencies
📦 requirements.txt
Here’s what you should add in your requirements.txt:

Copy
Edit
opencv-python
mediapipe
numpy
🙌 Credits
Developed by Dharun Kumar, B.Tech IT Student
Inspired by combining gesture control with calculator logic using MediaPipe's powerful hand-tracking solution.

🧠 Future Scope
Add support for multi-digit input (e.g., "12", "45")

Improve gesture robustness with dynamic feedback

Voice feedback for visually impaired users

Extend to scientific calculations

📸 Screenshots
Add a screenshot here of your project running (optional but recommended)

🛑 Exit Gesture
Make an 'X' sign with your index fingers of both hands (bring fingertips close) to gracefully exit the program.

🔓 License
MIT License. Use freely for learning or extending the project.

Feel free to ⭐️ this repo if you found it interesting or useful!

yaml
Copy
Edit

---

Let me know if you want me to generate a `requirements.txt` too or upload an image/screenshot you can include under "Screenshots" section.
