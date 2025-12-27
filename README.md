## ⚙️🛠 VISUAL STUDIO CODE SETUP FOR DSA WITH C++

````md
# 🚀 DSA VS Code C++ Setup (Fast & Clean)

This repository helps you **quickly run C++ DSA programs in VS Code** using **input/output text files** instead of typing inputs every time in the terminal.

Perfect for:
- DSA practice
- Competitive programming
- Clean debugging
- Avoiding repeated input typing

---

## 📦 Clone This Repository

Click the green **Code** button or run this in your terminal:

```bash
git clone https://github.com/VishwasSharma28/DSA-VS-Code-Setup.git
````

Then open the folder in **VS Code**:

```bash
code DSA-VS-Code-Setup
```

---

## 🗂️ Folder Structure Explained

After cloning, your project layout should look like this:

```
DSA-VS-Code-Setup/
│
├── main.cpp        # Your C++ code file
├── input.txt       # Input goes here
├── output.txt      # Output will be written here
├── .vscode/
│   └── tasks.json  # Build & run configuration
└── README.md
```

👉 **Important:**
Do NOT rename `input.txt`, `output.txt`, or `.vscode/tasks.json`.

---

## 🧠 How This Setup Works

* Your C++ program reads input from `input.txt`
* Output is redirected to `output.txt`
* VS Code builds & runs everything using **Ctrl + Shift + B**

No terminal typing. No copy-paste chaos.

---

## ✍️ Writing Your C++ Code

Open `main.cpp` and write your logic.

### Example:

```cpp
#include <bits/stdc++.h>
using namespace std;

int main() {
    int a, b;
    cin >> a >> b;
    cout << a + b;
    return 0;
}
```

---

## 📥 Providing Input

Open `input.txt` and type your input exactly as required:

```
10 20
```

---

## 📤 Viewing Output

After execution, check `output.txt`:

```
30
```

---

## ▶️ How to Run the Code (Very Important)

### On **Windows / Linux**

```
Ctrl + Shift + B
```

### On **macOS**

```
Cmd + Shift + B
```

This will:

* Compile `main.cpp`
* Run the program
* Redirect input/output automatically

---

## ⚙️ Behind the Scenes (tasks.json)

This repo uses a VS Code build task that:

* Compiles using `g++`
* Redirects input from `input.txt`
* Redirects output to `output.txt`

You **do not need to modify anything** unless you know what you’re doing.

---

## ❗ Common Mistakes to Avoid

❌ Renaming input/output files
❌ Deleting `.vscode` folder
❌ Writing code in a new random `.cpp` file
❌ Running via terminal instead of build task

---

## 🧪 Want to Create a New Problem?

1. Copy your logic
2. Replace code inside `main.cpp`
3. Update `input.txt`
4. Press **Ctrl + Shift + B**
5. Check `output.txt`

That’s it. Repeat forever.

---

## 🟢 Recommended VS Code Extensions

(Optional but 🔥)

* C/C++ (Microsoft)
* Code Runner (optional)
* Error Lens
* Better Comments

---

## 🏁 Final Notes

This setup is designed to:

* Save time
* Reduce friction
* Keep DSA practice distraction-free

If you’re grinding problems daily, this will **100% boost your flow**.

Happy coding 🚀
— Vishwas
