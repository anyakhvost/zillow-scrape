## Zillow Scrapper


## Requirements

1. Install python3, navigate to this repo and create a virtualenv
```
virtualenv .venv --python python3
```

2. Activate Virtualenv

```
source .venv/bin/activate
```

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

## To read CSV in Ruby, start IRB:
```
require 'csv'
table = CSV.parse(File.read("/Users/anyaroltsch/Desktop/florida_zip_codes.csv"), headers: true)
table.by_col[0].join(",")
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

### WV Zip Codes
25428,25403,25404,25405,25401,25402,25413,25419,25421,25420,25427,25430,25432,25438,25441,25443,25442,25446,25410,25414,25425



