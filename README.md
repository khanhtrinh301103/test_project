# test_project

cd /d D:\Test_project
conda activate env_data_analysis
cd Test_project
python app.py

Update:
Trong index.html 
thêm  class="rainprobability" vào div dưới này
<div>Rain probability: {{ weather['precipitation_probability'] }}%</div>

Trong app.py:
pip install flask-cors
from flask_cors import CORS


để CORS(server) ở dưới server.secrectkey

http://127.0.0.1:5000/

conda env create -f environment.yml
conda activate env_data_analysis
pip install pandas numpy matplotlib
pip install Flask
pip install pandas
pip install requests
pip install tensorflow
pip install scikit-learn
pip install dash
pip install -U spacy
python -m spacy download en_core_web_sm
pip install flask-cors
pip install fuzzywuzzy
pip install python-Levenshtein
