# DWAD

pkg upgrade -y && pkg update

pkg install git

pkg install python -y

pip install --upgrade pip

git clone https://github.com/stepanZero/ORION

cd ORION
 
cd dwadBOMB

pip install -r requirements.txt

python main.py
