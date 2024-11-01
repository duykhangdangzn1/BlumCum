pkg upgrade && pkg update -y
pkg install nano
pkg install python3
git clone https://github.com/ashtrobe/blumv2
cd blumv2
pip install -r requirements.txt
nano data.txt (paste your query id and then save by pressing CTRL + O + ENTER, close the file by CTRL + X 
python bot.py
