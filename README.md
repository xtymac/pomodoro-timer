# 🍅 Pomodoro Timer

A simple and elegant Pomodoro Timer built with Python and Tkinter. This application helps you boost productivity using the Pomodoro Technique - work for 25 minutes, then take a 5-minute break!

## ✨ Features

- **Work Sessions**: 25-minute focused work periods
- **Short Breaks**: 5-minute breaks between work sessions
- **Long Breaks**: 20-minute breaks after every 4 work sessions
- **Visual Timer**: Large, easy-to-read countdown display
- **Progress Tracking**: Check marks (✔️) for completed work sessions
- **Clean UI**: Minimalist design with a beautiful tomato icon
- **Reset Functionality**: Stop and reset the timer at any time

## 🚀 How to Run

### Prerequisites
- Python 3.x installed on your system
- tkinter (usually comes with Python)

### Installation & Usage
1. Clone this repository:
   ```bash
   git clone https://github.com/xtymac/pomodoro-timer.git
   cd pomodoro-timer
   ```

2. Run the application:
   ```bash
   python main.py
   ```

3. Click "Start" to begin your first Pomodoro session!

## 🎯 How to Use

1. **Start a Session**: Click the "Start" button to begin a 25-minute work session
2. **Work Focus**: The timer will show "Work" and count down from 25:00
3. **Break Time**: After work, enjoy a 5-minute break (or 20 minutes after 4 sessions)
4. **Track Progress**: See check marks appear for each completed work session
5. **Reset**: Click "Reset" to stop and restart the timer anytime

## 🔄 Pomodoro Cycle

The app follows the traditional Pomodoro Technique:
- **Sessions 1, 3, 5, 7...**: 25-minute work periods (Green)
- **Sessions 2, 4, 6...**: 5-minute short breaks (Pink)  
- **Sessions 8, 16, 24...**: 20-minute long breaks (Red)

## 📁 Project Structure

```
pomodoro-timer/
├── main.py          # Main application code
├── tomato.png       # Tomato icon for the UI
└── README.md        # This file
```

## 🛠️ Technologies Used

- **Python 3**: Core programming language
- **Tkinter**: GUI framework for the user interface
- **Math**: For time calculations and formatting

## 🎨 Color Scheme

- **Yellow Background**: `#f7f5dd` - Warm, comfortable workspace
- **Green Text**: `#9bdeac` - Work sessions and check marks
- **Pink Text**: `#e2979c` - Short breaks
- **Red Text**: `#e7305b` - Long breaks

## 🤝 Contributing

Feel free to fork this project and submit pull requests for any improvements!

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🎓 About

This Pomodoro Timer was created as part of a Python learning project. It demonstrates:
- GUI development with Tkinter
- Timer functionality with `window.after()`
- State management and user interaction
- Clean, user-friendly interface design

---

**Happy Productivity!** 🍅✨ 