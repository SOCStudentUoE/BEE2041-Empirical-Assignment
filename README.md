# BEE2041 Empirical Assignment

## Description
This project analyses the relationship between police force area financial reserves and performance outcomes using Jupyter Notebook and the Chrome WebDriver to scrape the latest performance data.

## Project Directory Layout
The project directory is organized as follows to ensure easy access and management of project components: 

/root # Root folder of the project
│
├── /data # Data files used and produced by the project
│ ├── /raw # Raw data, unchanged original source files
│ ├── /processed # Cleaned and processed data
│ └── /outputs # Graphs and output files generated from analyses
│
├── /docs # Documentation files and additional resources
│
├── /src # Source code for scripts and analysis
│
├── README.md # The top-level guide for this project
├── requirements.txt # Python dependencies needed for the project
└── .gitignore # Specifies intentionally untracked files to ignore

### Explanation of Key Directories

- **/data**: Contains all data files. `/raw` for unmodified data, `/processed` for cleaned data, and `/outputs` for results like charts.
- **/docs**: Includes all markdown and static documentation related files that help in understanding the project.
- **/src**: The main folder for all executable code, including Jupyter notebooks.

Each directory is structured to support easy navigation and scalability of the project.



## Prerequisites
- Python 3+
- Jupyter Notebook

Refer to requirements.txt in the github repository for further python package requirements.

## Chrome WebDriver Setup
1. Download Chrome WebDriver from [ChromeDriver](https://googlechromelabs.github.io/chrome-for-testing/#stable).
2. Ensure the WebDriver version matches your Chrome browser version.
3. Extract and place `chromedriver` in your project directory or add it to your PATH.

## Running the Notebook
1. Navigate to Jupyter Notebook "blog.ipynb" and open it.
2. Run the first 9 cells sequentially from top to bottom.
3. Before running the 10th cell, update the path (variable titled "chromedriver_path") to the chromedriver you downloaded previously.
4. Run the webscraping script in cell 10. This script should take approximately 10 minutes to gather the required data. If initialisation fails, try re-running the cell once your network settings are verified to be working properly.
5. Run the rest of the cells from top to bottom to generate cleaned data and data analysis on that data.

## Author
Samuel O. Corkill 
## Special Thanks
- Damian Clarke
- Wiktoria Okla
- Ben Godfrey
- Rory Mitchell
- Henry Perry
- Tobi Soetjianto 
- ChatGPT!
