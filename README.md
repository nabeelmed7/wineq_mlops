Create an enviornment using:
        conda create -n <env-name> python=3.11 -y

Activate the enviornment using:
        conda activate <env-name>

Create a requirements.txt file.

Install all the requirements using:
        pip install -r requirements.txt

Initialize GIT using:
        git init

Initialize dvc using:
        dvc init

Add data to dvc using:
        dvc add data_given/wine_quality.csv

To add all the contents to the staging area:
        git add .

To commit:
        git commit -m "First commit"

Create an empty repo on GIThub and then upload all the files opf this local to that remote repo using:
        git remote add origin https://github.com/nabeelmed7/wineq_mlops.git
        git push origin main
