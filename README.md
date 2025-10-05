HVM Panel

HVM Panel is a lightweight and easy-to-use web panel built with Python and Flask. It provides a simple interface for managing virtual machines and related services.

🧠 Features

Simple and fast Flask-based web interface

Real-time updates via Socket.IO

Docker and SSH (Paramiko) integration

User authentication (Flask-Login)

System stats and resource tracking (psutil)

Rate limiting for security (flask-limiter)

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
python3 hvm.py```

🧾 License

This project is licensed under the HVM Panel License (Permissive — Liability Disclaimer).

The author is not responsible for how users deploy, modify, or use this software.
You are free to fork, modify, distribute, or use this code as you wish, at your own risk.
See the LICENSE
 file for full details.
