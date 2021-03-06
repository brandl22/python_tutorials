# Installation
If you're unfamiliar with python, we recommend you use Anaconda's Python distribution. All examples are tested with python 3.6.1.

1. Install Python 3.6.1 [We recommend Anaconda's distribution](https://www.anaconda.com/download/)
2. Open the "Anaconda Prompt" -- or whatever shell you commonly use. 
2. `conda install pandas jupyter matplotlib seaborn scikit-learn` -- if you use python regularly create a condenv or virutal env.
3. `pip install sdd_api`
3. `git clone https://github.com/SportsDataDirect/python_tutorials/`
3. `cd python_tutorials`
4. Rename credentials.py.template to credentials.py and fill with:
    - your username and password to [Sports Data Direct](https://www.sportsdatadirect.com)
    - your client_id and client_secret from [Your Profile](https://www.sportsdatadirect.com/users/profile)
4. Run `jupyter notebook` and start exploring! 
    - Our [Data Access Example Notebook](https://nbviewer.jupyter.org/github/sportsdatadirect/python_tutorials/blob/master/Python%20Data%20Access%20Example.ipynb) is a good place to start. 
