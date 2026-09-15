## Python for Financial Data Analysis

September 2026 - Toby Dussek

* 10:00 start
* 11:30 morning break (20 mins)
* 1:00 lunch (1 hr)
* 3:30 afternoon break (20 mins)
* 5:00 done

#### Course website: 
`https://github.com/onionmccabbage/pythonOneSept2026`

### What we will do today
This day covers Python and Data Analysis in preparation for later work with generative  tools
* Welcome, tech check and where to get help & resources
* Comparing Excel and Python
* Overview: using Jupyter
* Writing Python code
* Data Types and Collections
* Assignment 1 Exercises 1 & 2
* Conditional Logic and Loops
* Using range()
* Assignment 1 Exercises 3, 4 & 5 (optionally 6)
    - code snippet: `grades = {'Bob':71, 'Alice':65, 'Jim':70, 'Jen':90, 'Tim':86, 'Trish':85, 'Tony':75}`
* Functions
* Using Numpy Arrays
* Assignment 1 Exercises 7 & 8 
* Using Pandas and dataFrames
* Working with .csv and .xlsx data
* Statistical financial data analysis
* Assignment 2 Exercises 1 & 2




#### Additional Content
* Merging and joining data sources
* Assignment 2 Exercises 3 & 4
* Moving Averages
* Data sampling frequency
* Assignment 2 Exercises 5, 6 & 7








### Things to watch for
`https://raw.githubusercontent.com/onionmccabbage/pythonOneSept2026/refs/heads/main/StockData/SP500.csv`
#### Assignment 1
- When reading in the supplied .csv and .xlsx files you will often need to add `date_format='%m/%d/%y'` 
#### Assignment 2
- Exercise 1: use `format='%m/%d/%y'` (instead of format=r'%Y-%m-%d')
- Exercise 6: `fundamentals.csv` is in `ExData` folder
  - step 6: may be better off using:
    - `ba_fin['ROA'] = ba_fin['ROA'].ffill()`
- Exercise 7: file `ff3.csv` is actually called `ff3_monthly.CSV` (in `ExData` folder)
- General: You may get this problem/solution: `ValueError: Invalid frequency: M. Failed to parse with error message: ValueError("'M' is no longer supported for offsets. Please use 'ME' instead.")`


Course: 	Python for Finance September 14-16 2026
Survey code: 	ORRFOX
Survey link: 
  https://www.coursecheck.com/event/ORRFOX
