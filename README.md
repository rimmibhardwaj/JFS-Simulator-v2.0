# JFS Simulator v2.0

An interactive and educational **Journaling File System (JFS) Simulator** that demonstrates how modern operating systems use **Write-Ahead Logging (WAL)**, transaction management, crash recovery, and journaling techniques to maintain file system consistency.

This project is designed for students learning:

* Operating Systems
* Database Recovery Concepts
* Transaction Management
* File System Internals
* WAL & Journaling Mechanisms

---

## 🚀 Features

### ✅ Core Features

* Real-time Journaling File System simulation
* Write-Ahead Logging (WAL)
* Transaction-based operations
* Crash simulation & recovery system
* REDO and UNDO recovery process
* Disk block visualization
* Live journal log tracking
* Interactive transaction timeline

### ✅ Advanced Features

* Step-by-step replay system
* Analytics dashboard with charts
* File system block monitoring
* Multiple journaling modes
* State persistence using localStorage
* Export logs and simulator state
* Dark/Light theme support
* Custom accent colors

---

## 🧠 Concepts Demonstrated

This simulator helps visualize important Operating System concepts:

* Write-Ahead Logging (WAL)
* ACID Properties
* Journaling File Systems
* Crash Consistency
* Transaction Lifecycle
* Checkpointing
* REDO/UNDO Recovery
* Log Sequence Numbers (LSN)
* Disk Block Allocation

---

## 🛠️ Tech Stack

| Technology         | Purpose                  |
| ------------------ | ------------------------ |
| HTML5              | Structure                |
| CSS3               | Styling & Layout         |
| Vanilla JavaScript | Core Logic               |
| Chart.js           | Analytics Charts         |
| Node.js            | Local Development Server |

---

## 📁 Project Structure

```bash
OS_Project/
│
├── index.html              # Main application UI
├── server.js               # Local Node.js server
├── README.md               # Project documentation
│
├── css/
│   └── styles.css          # Styling and themes
│
└── js/
    ├── app.js              # Main application logic
    ├── simulator.js        # WAL & transaction engine
    └── ui.js               # UI rendering and interactions
```

---

## ⚡ Getting Started

### Method 1 — Open Directly

Simply open:

```bash
index.html
```

in your browser.

---

### Method 2 — Run with Node.js

```bash
node server.js
```

Then open:

```bash
http://localhost:3000
```

---

### Method 3 — Python HTTP Server

```bash
python -m http.server 3000
```

Then open:

```bash
http://localhost:3000
```

---

## 🎯 How to Use

### Start a Transaction

1. Open the Simulator page
2. Click **Start Transaction**
3. Enter:

   * File Name
   * Data
   * Block ID
   * Operation Type
4. Click **Write Data**
5. Click **Commit Transaction**

---

### Crash Recovery Demo

1. Start a transaction
2. Write data without committing
3. Click **Simulate Crash**
4. Initialize recovery sequence
5. Watch REDO/UNDO recovery in action

---

## 📊 Main Modules

| Module      | Description                     |
| ----------- | ------------------------------- |
| Dashboard   | System overview                 |
| Simulator   | Transaction execution           |
| Journal Log | WAL records                     |
| File System | Disk block visualization        |
| Replay      | Step-by-step execution replay   |
| Analytics   | Charts and statistics           |
| Learn JFS   | Educational learning section    |
| Settings    | Theme & simulator configuration |

---

## ⌨️ Keyboard Shortcuts

| Shortcut     | Action               |
| ------------ | -------------------- |
| Ctrl + T     | Start Transaction    |
| Ctrl + W     | Write Data           |
| Ctrl + Enter | Commit Transaction   |
| Ctrl + Z     | Rollback Transaction |

---

## 📸 Suggested GitHub Topics

```text
operating-systems
file-system
journaling-file-system
wal
crash-recovery
transaction-management
javascript
os-project
computer-science
education
simulator
```

---

## 🌟 Future Improvements

* Multi-user transaction simulation
* Distributed logging support
* More journaling algorithms
* Better disk visualization
* Performance benchmarking
* Real-time synchronization

---

