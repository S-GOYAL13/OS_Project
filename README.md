## 📘 OSProject – Operating System Simulator

Welcome to **OSProject**, a simplified Operating System simulation built in C++. This project demonstrates core OS concepts such as process scheduling, memory management, and system calls through structured code and JSON-based input.

---

### 🚀 Features

- ⚙️ **Process Scheduling**
- 💾 **File & Memory Management**
- 🔄 **Input/Output Simulation**
- 📊 JSON-based configuration and results
- 💡 Written entirely in modern C++

---

### 📁 Project Structure

```bash
.
├── code.cpp               # Main C++ source code
├── input.json            # Input data for processes/files
├── json.hpp              # JSON parser header (nlohmann/json)
├── .vscode/              # VSCode config files
└── README.md             # This file
```

---

### 🛠️ Requirements

- C++ compiler (G++ recommended)
- [nlohmann/json](https://github.com/nlohmann/json) (already included as `json.hpp`)

---

### ▶️ How to Run

1. **Clone the repo**  
```bash
git clone https://github.com/S-GOYAL13/OS_Project.git
cd OS_Project
```

2. **Compile and Run**  
```bash
g++ code.cpp -o os_simulator
./os_simulator
```

---

### 📥 Input Format (input.json)

```json
{
  "processes": [
    { "pid": 1, "arrival": 0, "burst": 5 },
    { "pid": 2, "arrival": 2, "burst": 3 }
  ]
}
```

*Feel free to customize the input!*

---

### 🧠 Learnings & Concepts

- Process lifecycle
- CPU & I/O scheduling
- JSON parsing in C++
- Modular program design

---

### 👩‍💻 Author

**Sanya Goyal**  
📫 [sanya.goyal.ug23@nsut.ac.in](mailto:sanya.goyal.ug23@nsut.ac.in)  
🌐 [GitHub Profile](https://github.com/S-GOYAL13)

---

### ⭐️ If you like this project...

Give it a ⭐️ on GitHub – it motivates me to keep building!