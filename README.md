# Polyfill.io Checker

This project provides a Python script to check if websites listed in an Excel file are using `polyfill.io`. The results are written back to the Excel file.

## Requirements

Ensure you have Python installed. You also need the following Python libraries:

- `requests`
- `openpyxl`
- `beautifulsoup4`

You can install these libraries using `pip`:

```sh
pip install requests openpyxl beautifulsoup4

```


Prepare Your Excel File:

Ensure your Excel file has URLs listed in the first column, starting from the second row (row 1 is assumed to be the header).

Update the Script:

Update the file_path variable with the path to your Excel file.

Run the Script:

Execute the script using Python:

python polyfill_checker.py

The script will read each URL, check if polyfill.io is used (either directly or via Google Tag Manager), and write the result (Yes, No, or Error) in the second column of the Excel file.