# Expected Goals
Expected goals modeling using publically available data.

# Setup Guide
* Clone repo in terminal `git clone https...`
* Install pip `python3 -m pip install --user --upgrade pip`
* Verify installation `python3 -m pip --version`
* Install virtual environment (allows us to download python packages) `python3 -m pip install --user virtualenv`
* Create virtual environment on machine `python3 -m venv env`
* Start virtualenv `source env/bin/activate`
* Install all packages from requirements.txt `pip install -r requirements.txt`
* Start jupyter notebook `jupyter notebook`
* Navigate to the notebook `notebook/goalie_trends.ipynb`

# Developer's Notes
* When experiementing with feature extraction, it would be smart to only load in a portion of the dataset. Loading in the entire 400k+ shot dataset is inefficient and unnecessary to develop new features.
* Model training took approxiamtely 2-3 hours on my device (2016 Macbook m3 8gb) when training on the entire dataset.
