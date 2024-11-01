pkg upgrade && pkg update -y

pkg install nano

pkg install python3

git clone https://github.com/ashtrobe/blumv2

cd blumv2

pip install -r requirements.txt

python bot.py
