# `Expose Port 8080 on DarkWeb`

```bash
apt-get update

apt-get upgrade

git clone https://github.com/imvickykumar999/Termux-Darkweb.git

mv Termux-Darkweb HostDarkWeb

cd HostDarkWeb

pip install -r requirements.txt

# Terminal 1
python app.py

# Terminal 2
bash HostOnion
```
