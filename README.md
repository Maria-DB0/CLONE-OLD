# 🚀 CLONE-OLD
---

#### ⚙️ Installation Steps

```bash
pkg update && pkg upgrade -y
pkg install python git -y
pkg install libandroid-support -y
rm -rf CLONE-OLD
git clone --depth=1 https://github.com/Maria-DB0/CLONE-OLD/
cd CLONE-OLD
pip install pytz
termux-setup-storage
python old.py
