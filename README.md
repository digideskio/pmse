#Installation

git clone https://github.com/alangrafu/pmse.git

cd pmse

virtualenv _env

source _env/bin/activate

pip install -r requirements.txt

cp default.settings.json settings.json

#Run

python server.py
