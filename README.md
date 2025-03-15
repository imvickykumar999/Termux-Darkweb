# `Expose Port 8080 on DarkWeb`

## `Terminal 1`

```bash
apt-get update

apt-get upgrade

git clone https://github.com/imvickykumar999/Termux-Darkweb.git

cd HostDarkWeb

bash HostOnion
```

## `Terminal 2`

```bash
cd FlaskWebsite

pip install -r requirements.txt

python app.py --port 8080
```
