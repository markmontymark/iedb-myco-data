# iedb-myco-data

Task to denormalize a myco data file (csv) but taking last N columns per line
and creating a line for each extra column

## Usage:

    git clone https://github.com/markmontymark/iedb-myco-data
		cd iedb-myco-data
		npm install
		node ./ < your-input-file.csv > where-you-want-output-to-go.csv
