
# Automated Coding from PDFs

This project extracts necessary information from PDF news and automatically codes them in separate columns. This information includes titles, dates, and some sentences containing specific words. Depending on these particular words, it automatically codes them in a separate column as "1" if the news includes these words; otherwise, it codes as 0.

# Description of the Repository
 - Automated Coding from PDFs/: Includes codes and package installations in R.
 - AutomatedCodingfromPDFs.Rmd/: Rmd file that you can open in R and run the codes just by changing the path of the folder. 

# Usage
- Install and Load Necessary Packages: Use the script in the Automated Coding from the PDFs folder to install and load necessary packages.
- Define the Path of the PDFs folder: Find the path of the PDFs folder on your computer and change the code line accordingly
- Run the function that collects each PDF into a single data frame
- After defining the title pattern, extract titles and write them in a separate column.
- After defining the date pattern, extract the dates and write them in a separate column.
-Text Cleaning Process: Remove white spaces and create a new column containing a clean text version.
- Define particular words to check whether these texts include them or not.
- Code the news as 1 or 0 depending on whether they include particular words.
- Extract the sentences that only include particular words and write them in a separate column.
- Save the data frame as a CSV or Excel file. 



