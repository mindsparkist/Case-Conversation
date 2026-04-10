## Case Converter

**A sleek, professional-grade text utility designed with iOS-inspired aesthetics.**

This web app provides a minimalist, high-performance interface for all your text transformation needs. Built with a focus on clean design and functional efficiency, it allows you to switch between various casing formats instantly.

**[🌐 Live Demo on Netlify](https://merry-quokka-497275.netlify.app/)** | **[📂 GitHub Pages Mirror](https://shuvradip2019.github.io/Case_Conversation/)**

-----

### 🎨 Design Philosophy

Inspired by **Apple’s Human Interface Guidelines**, this tool features:

  * **Glassmorphism:** Soft, blurred backgrounds and translucent layers.
  * **Premium Typography:** Utilizing system fonts for a native feel.
  * **Responsive Layout:** Fully optimized for mobile, tablet, and desktop viewing.
  * **Interactive Feedback:** Subtle scale animations and haptic-ready interactions.

### ⚙️ Conversion Features

The app supports eight distinct text transformation modes:

| Mode | Input Example | Output Example |
| :--- | :--- | :--- |
| **Lower Case** | HELLO WORLD | hello world |
| **Upper Case** | hello world | HELLO WORLD |
| **Capitalized Case** | hello world | Hello World |
| **Sentence case** | hello world. it is me. | Hello world. It is me. |
| **Title Case** | a story in the woods | A Story in the Woods |
| **Toggle Case** | hElLo | HeLLo |
| **Alternating Case** | hello | hElLo |
| **Sentence\_Case** | Hello World | hello\_world |

-----

### 🚀 Technical Stack

  * **Frontend:** HTML5, CSS3 (Custom Glassmorphism properties).
  * **Logic:** Vanilla JavaScript for high-speed string manipulation.
  * **Icons:** Optimized vector icons for a sharp look on Retina displays.

### 🛠️ How to Use

1.  **Paste** your text into the main input area.
2.  **Select** the desired case format from the action grid.
3.  **Copy** the result to your clipboard with one click.

-----

### 📬 Contact & Contribution

Feel free to fork this repository if you want to add more features or customize the UI further.

  * **GitHub:** [shuvradip2019](https://www.google.com/search?q=https://github.com/shuvradip2019)
  * **Portfolio:** [shuvradipchakraborty.me](http://www.shuvradipchakraborty.me)

Here is a clean, minimalist **README.md** tailored for your new app. It mirrors the simplicity of the interface while providing exactly what a visitor needs to know.

---

# Name Formatter

An ultra-minimalist web utility for standardizing name casing instantly. 

**Live Demo:** [https://stupendous-sopapillas-9a831e.netlify.app/](https://stupendous-sopapillas-9a831e.netlify.app/)

## ✨ The Philosophy
Most tools are cluttered with buttons, headers, and ads. This app follows the **"Input is Output"** principle. No unnecessary clicks—just the result you need.

## 🚀 Features
* **Live Conversion:** Formats text the moment you stop typing or paste.
* **Standard Formatting:** Converts any text to `First Name, Middle Name(s), Surname` (e.g., *SARAH JANE SMITH* → *Sarah Jane Smith*).
* **Contextual UI:** A sleek "Copy" button appears only when you have something to copy.
* **Zero Friction:** No "Submit" or "Convert" buttons required.

## 🛠️ How it Works
The app uses a 300ms "debounce" timer. When you paste a name:
1. It waits for the input to finish.
2. It strips extra whitespace.
3. It forces the string to lowercase and capitalizes the first letter of every name segment.
4. It updates the field in-place for immediate use.

## 💻 Tech Stack
* **HTML5**
* **CSS3** (Fluid typography & Flexbox)
* **Vanilla JavaScript** (Debounced event listeners)

---

### License
MIT — Feel free to use, modify, and distribute.
