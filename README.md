HVM Panel

HVM Panel is a lightweight and easy-to-use web panel built with Python and Flask. It provides a modern interface for managing virtual machines and system resources with real-time updates and secure access.

🧠 Features

⚡ Built with Flask for speed and simplicity

🔐 Integrated user authentication (Flask-Login)

🐳 Docker and SSH management (Paramiko)

📊 Real-time system monitoring (psutil + Socket.IO)

🚦 Built-in rate limiting (flask-limiter)

🧩 Easy to extend and modify

📄 License

This project is licensed under the HVM Panel License (Permissive — Liability Disclaimer).

Licensed under the HVM Panel Redistribution License (No Responsibility) — see LICENSE for full terms.
You are free to fork, modify, distribute, or use this code as you wish, entirely at your own risk.

💬 Support

If you encounter any issues, bugs, or have suggestions, please open an Issue or Pull Request on this repository.

⚙️ Installation

Follow these steps to install and run HVM Panel on your system:

```bash
sudo apt update
sudo apt install python3 -y && apt install pip -y
git clone https://github.com/ItsMePara123/VmPanel
cd VmPanel
cd hvm
pip3 install flask flask-socketio flask_login docker paramiko python-dotenv psutil flask-limiter
pip install -r requirements.txt
python3 hvm.py
