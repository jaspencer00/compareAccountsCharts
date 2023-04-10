# Github README file

## Introduction
This program takes in data from two Excel sheets, `sheet1` and `sheet2`, and performs a matching algorithm to find the closest description match between the two sheets. The program then creates a new dataframe, `result`, with the matched data and saves it as a new Excel sheet.

## How it works
The program uses a loop to iterate through each row in `sheet1` and finds the closest match in `sheet2`. It uses the `find_closest_match` function to find the closest match between the two descriptions. 

Once a match is found, the program creates a new row in `result` with the matched data. If no match is found, a message is printed to the console.

## Requirements
- Python 3
- Pandas
- Numpy

## Usage
1. Install the necessary dependencies by running `pip install pandas numpy`.
2. Clone this repository to your local machine.
3. Update the file paths for `sheet1` and `sheet2` in the code to match the location of your Excel sheets.
4. Run the program by running `python match_descriptions.py`.
5. The resulting matched data will be saved as a new Excel sheet in the same directory as the program.

## License
This program is licensed under the MIT license. See the LICENSE file for more information.
