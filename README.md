# 🎹 Hand-Controlled MIDI Chord Player (D Major Scale)

This Python project allows you to play chords in the **D Major scale** using your hand gestures. By detecting finger movements through a webcam, specific chords are triggered using the MIDI sound system.

---

## 📦 Features

- 🎵 Play chords by lifting specific fingers
- ✋ Supports both left and right hands
- 🎼 Chords mapped to each finger (e.g., D Major, G Major, A Major, etc.)
- 🎹 MIDI playback with acoustic piano
- ⏱️ Sustained chords that stop automatically after a delay

---

## 🧠 Tech Stack

- [OpenCV](https://opencv.org/) — for webcam frame capture
- [cvzone](https://github.com/cvzone/cvzone) — for easy hand tracking
- [pygame.midi](https://www.pygame.org/docs/ref/midi.html) — for MIDI sound playback
- [threading](https://docs.python.org/3/library/threading.html) — for non-blocking chord stopping

---

## 🎶 Chord Mapping (D Major Scale)

Each finger on both hands is mapped to a chord:

| Finger   | Chord      | Notes         |
|----------|------------|---------------|
| Thumb    | D Major    | D, F#, A      |
| Index    | E Minor    | E, G, B       |
| Middle   | F# Minor   | F#, A, C#     |
| Ring     | G Major    | G, B, D       |
| Pinky    | A Major    | A, C#, E      |

---

## 🛠️ Installation & Setup

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/hand-midi-chords.git
cd hand-midi-chords
```

### 2. Install Dependencies
```bash
pip install opencv-python cvzone pygame
```

### 3. Run the Script
```bash
python hand_dscale.py
```

---

## ✅ Requirements

- Python 3.7+
- Webcam
- A MIDI-compatible sound device (most systems have one by default)
- Working `cvzone` and `pygame.midi` installation

---

## ⌨️ Controls

- Raise fingers to play chords
- Lower fingers to stop chords after a 2-second delay
- Press `Q` to quit the application

---

## 📷 Preview

![preview-gif](https://your-link-to-gif-or-image.com)  
*A visual example of hand control triggering piano chords.*

---

## 🙌 Acknowledgements

- [cvzone](https://github.com/cvzone/cvzone) by Murtaza Hassan
- [pygame](https://www.pygame.org/news) — MIDI module for real-time sound playback

---

## 📜 License

This project is licensed under the MIT License.

---

## 🚀 Future Enhancements

- Add more scales and dynamic chord sets
- Visual chord indicators on screen
- Multi-instrument MIDI support
