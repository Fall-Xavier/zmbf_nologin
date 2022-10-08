### Buat yang pertamakali install termux
```
pkg update && pkg upgrade
pkg install git python
cd $HOME
rm -rf bot_share
git clone https://github.com/Fall-Xavier/bot_share
cd bot_share
python -m pip install -r bahan.txt
python build.py
python run.py
```

### Buat yang sering main termux
```
cd $HOME
rm -rf bot_share
git clone https://github.com/Fall-Xavier/bot_share
cd bot_share
python build.py
python run.py
```
