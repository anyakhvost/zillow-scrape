## Zillow Scrapper


## Requirements

1. Install python3, navigate to this repo and create a virtualenv
```
virtualenv .venv --python python3
```

2. Activate Virtualenv
```

in windows:

python3 -m venv /path/to/new/virtual/environment


```

3. Install requirements
```
pip install -r requirements-python3.txt
```


## Usage

```
python zillow.py <zipcode>
```
This will create a CSV file in the same directory.
You can pass a list of zipcodes separated by comma (no space between zipcodes):
```
python zillow.py 25420,23420
```

## Git Usage

### To create a new branch:
```
git checkout master
git pull origin master
git checkout -b <branch_name>
```

### Check what has been modified:
```
git status
```

### Add changes to the branch:
```
git add -A
```

### Commit changes:
```
git commit -m <"something">
```

### Push code to a remote:
```
git push origin <branch name no quoute>
```

