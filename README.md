# 🔐Random Password Generator (CLI Tool)

A simple and customizable command-line interface (CLI) tool to generate secure, random passwords. Ideal for developers, system admins, or anyone needing strong passwords fast and effortlessly.

## 📦Features

1. Generate strong random passwords
2. Choose password length
3. Include/exclude:
    - Uppercase letters
    - Lowercase letters
    - Numbers
    - Special characters
4. Copy password directly to clipboard (optional)
5. Cross-platform support:

    [![macOS](https://img.shields.io/badge/mac%20os-000000?style=for-the-badge&logo=macos&logoColor=F0F0F0)](https://www.apple.com/macos/macos-sequoia/)[![Windows](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)](https://www.microsoft.com/windows)[![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)](https://www.linux.org)


## 🚀 Getting Started

### ✅ Prerequisites

- Python 3.6+
- pip (Python package manager)

### 🔧 Installation

Clone the repository:

```
git clone https://www.github.com/Jaydev-1510/random-pswd-cli.git
cd random-pswd-cli
```

(Optional) Create a virtual environment:

```
python -m venv venv
```
On non-Windows OS devices
```
source venv/bin/activate
```
On Windows OS
```
source venv\Scripts\activate
```
### 🛠️ Usage

Run the password generator:
```
python pswd-generator.py
```

### 🔤 Options

You can customize the password generation via CLI flags:

```
python pswd-generator.py --length 16 --uppercase --lowercase --digits --symbols
```

Available flags:
| Flag          | Description                                           | Default |
| ------------- | ----------------------------------------------------- | ------- |
| `--length`    | Length of the password                                | 12      |
| `--uppercase` | Include uppercase letters (A-Z)                       | False   |
| `--lowercase` | Include lowercase letters (a-z)                       | True    |
| `--digits`    | Include digits (0-9)                                  | True    |
| `--symbols`   | Include special characters (!@#\$ etc.)               | False   |
| `--copy`      | Copy the password to clipboard (requires `pyperclip`) | False   |


### 🔍 Example
```
python pswd-generator.py --length 20 --uppercase --digits --symbols --copy
```
> Output: Generated Password: 8$GfL9@dN3w#XZr2pWqY (Copied to clipboard ✅)


## 📁 Project Structure

```
  random-password-cli/
│
├── pswd-generator.py    # Main CLI script
├── requirements.txt         # Dependencies
└── README.md                # Documentation
```


## 🤝 Contributing

Contributions are welcome! Feel free to open issues or submit PRs.

1. Fork the repo
2. Create a new branch (git checkout -b feature/feature-name)
3. Commit your changes (git commit -am 'Add some feature')
4. Push to the branch (git push origin feature/feature-name)
5. Open a pull request


## 📄 License

[![Licence](https://img.shields.io/github/license/Ileriayo/markdown-badges?style=for-the-badge)](./LICENSE)

This project is licensed under the MIT License. See [LICENSE](.LICENSE) for details.


## 🙌 Acknowledgments

- Inspired by the need for quick, secure password creation.
- Thanks to Python's secrets and argparse libraries.


Made purely with 🧠 and [![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)](https://www.python.org)

💖 Thank You!