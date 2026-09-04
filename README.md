# 📂 Automated File Deduplication System

A Python-based automation tool that detects and removes duplicate files using MD5 hashing. The system scans directories recursively, identifies duplicate files based on their content, and removes redundant copies to optimize storage utilization and improve file management efficiency.

---

## 🚀 Features

- 🔍 Detects duplicate files using MD5 hashing
- 📁 Recursively scans all folders and subfolders
- ⚡ Fast file comparison based on checksum values
- 🗑️ Automatically removes duplicate files
- 📊 Displays duplicate file information before deletion
- 💾 Helps optimize disk storage usage
- 🖥️ Simple command-line execution

---

## 🛠️ Technologies Used

- Python 3.x
- os
- hashlib

---

## 📂 Project Structure

```text
Automated-File-Deduplication-System
│
├── src/
│   └── file_deduplicator.py
│
├── screenshots/
│   ├── execution.png
│   └── duplicate_files_removed.png
│
├── sample_output/
│   └── sample_report.txt
│
├── README.md
├── requirements.txt
├── .gitignore
└── LICENSE
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/atharv-bhosale11/Automated-File-Deduplication-System.git
cd Automated-File-Deduplication-System
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Usage

Run the script:

```bash
python file_deduplicator.py
```

The application will:

1. Scan the target directory.
2. Calculate MD5 checksums of all files.
3. Detect duplicate files.
4. Display duplicate file information.
5. Remove redundant copies automatically.
6. Display the total number of deleted files.

---

## 🔐 How It Works

### Step 1: File Scanning

The system traverses all directories using:

```python
os.walk()
```

### Step 2: Hash Generation

Each file is processed and an MD5 hash is generated:

```python
hashlib.md5()
```

### Step 3: Duplicate Detection

Files with identical hash values are considered duplicates.

### Step 4: Duplicate Removal

The first file is preserved while redundant copies are deleted automatically.

---

## 📸 Screenshots

### Duplicate File Detection

_Add screenshot here_

### Duplicate File Removal

_Add screenshot here_

---

## 📈 Future Enhancements

- Interactive menu-driven interface
- Duplicate file report generation
- File recovery before deletion
- GUI-based dashboard
- Email notification support
- Multi-threaded scanning for large directories
- SHA-256 hashing support

---

## 🎯 Use Cases

- Storage optimization
- File management automation
- Duplicate media cleanup
- Backup directory maintenance
- Large-scale file organization

---

## 👨‍💻 Author

**Atharv Tushar Bhosale**

GitHub: https://github.com/atharv-bhosale11

---
