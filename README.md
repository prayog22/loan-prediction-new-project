# loan-prediction
predict which of the customers will have their loan approved.

Launch the ec2 instance with t2.medium/ssh/all traffic/ubuntu image/30gb storage.
sudo apt-get update && sudo apt-get upgrade -y      
sudo apt install python3-venv -y          (install python environment)
python3 -m venv MLPRO
source MLPRO/bin/activate                 (activate env)
mkdir mlproject                           (create one project directory)
cd mlproject                              (enter in project directory)
chmod 777 loan-prediction
cd loan-prediction
git clone https://github.com/vipulwarthe/loan-prediction.git
pip install ipykernel -U --force-reinstall
create setup.py and requirements.txt file in loan-prediciton folder or repo and put code and packges.
pip install -r requirements.txt
pip install imbalanced-learn
