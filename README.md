# KMP-DSA
finding motif using visualization
🔍 KMP Algorithm Visualization using Python

A GUI-based visualization of the Knuth–Morris–Pratt (KMP) string matching algorithm, implemented in Python using Tkinter and Matplotlib, with explicit use of Stack, Queue, and Linked List data structures.

This project helps students understand how KMP works internally by showing character-by-character comparisons and match detection visually.

📌 Features

✅ Implementation of KMP string matching algorithm

🎨 Graphical visualization of text and pattern matching

🧱 Explicit use of:

Stack – during LPS (Longest Prefix Suffix) construction

Queue – to store all pattern match positions

Linked List – to maintain ordered match results

⏱️ Step-by-step animation using Tkinter.after()

📍 Highlights:

Current comparison index

Successful pattern matches

🧪 User-defined Text and Pattern input

🧠 Algorithm Used

Knuth–Morris–Pratt (KMP) Algorithm

Time Complexity:

O(n + m)

where n = length of text, m = length of pattern

Space Complexity:

O(m) for LPS array

The KMP algorithm avoids redundant comparisons by using the LPS array, making it more efficient than naive string matching.

🛠️ Technologies Used
Technology	Purpose
Python	Core programming language
Tkinter	GUI interface
Matplotlib	Visualization
VS Code	Development environment
📂 Project Structure
KMP-Visualization/
│
├── kmp_visualizer.py     # Main application file
├── README.md             # Project documentation
└── requirements.txt      # Dependencies

⚙️ Installation & Setup
1️⃣ Clone the Repository
cd KMP-Visualization

2️⃣ Install Dependencies
pip install matplotlib


⚠️ Tkinter comes pre-installed with Python.

3️⃣ Run the Application
python kmp_visualizer.py

🖥️ How the Visualization Works

🔵 Blue bars → Characters of the input text

🟠 Orange bar → Current character comparison

🟢 Green bars → Successful pattern match

The animation updates every 600 ms, allowing clear observation of each comparison.

🧪 Example

Text:

ABABDABACDABABCABAB


Pattern:

ABABCABAB


Output:

Pattern found at position: 10

📚 Educational Value

This project is ideal for:

Data Structures & Algorithms labs

Algorithm visualization assignments

Understanding pattern matching algorithms

Viva and technical presentations

Mini-project submission

🚀 Future Enhancements

🔄 LPS array visualization

🎚️ Speed control slider

📊 Comparison counter

💾 Export visualization as video

🌐 Web-based version

Submitted by:
Prapti Poudel 
Nayana Shakya
