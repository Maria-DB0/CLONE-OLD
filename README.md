# 🚀 CLONE-OLD
---

#### ⚙️ Installation Steps

```bash
pkg update && pkg upgrade -y
pkg install python git -y
pkg install libandroid-support -y
rm -rf Meta-Hunter
git clone --depth=1 https://github.com/Maria-DB0/CLONE-OLD/
cd Meta-Hunter
pip install pytz
termux-setup-storage
python old.py
