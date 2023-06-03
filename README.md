# Utilizing Data Visualization Techniques to Improve a Landscaping Company

This project explores the use of data visualizations to enhance company performance. It discusses various approaches, data processing techniques, and data visualization methods, while incorporating personal experiences. The report is a compilation of selected portions created for personal presentation, drawing from professor's notes and additional research.

Although my background lies in software development, I delved into data science out of curiosity and found it to be an enriching experience. The guidance provided by my professor, Terrence Tricco, and resources like Stack Overflow, Matplotlib, and Seaborn documentation were instrumental in my progress. The project utilized three datasets—employees.csv, landscape.csv, and calendar.csv—to improve the company by identifying sub-goals related to job types and customer attributes.

Data processing techniques were applied to the datasets, involving multiple code iterations, refinement, and assumptions. Quick visualizations facilitated data exploration, leading to the creation of four visualizations, including an interactive one. These visualizations demonstrate how leveraging concepts contributes to company improvement. The coding process was carried out in Jupyter notebooks, and the report includes the necessary code for reproducing the visualizations.

This project showcases the significance of data visualization in driving informed decision-making and achieving organizational goals.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Directory Structure](#directory-structure)
- [Attribution](#attribution)

## Installation

To use this project, you need to have Jupyter Notebook installed on your machine. If you don't have it installed, you can follow these steps to get started:

1. Install Python: This project requires Python to be installed. You can download Python from the official website: [python.org](https://www.python.org/downloads/)
2. Install Jupyter Notebook: Once Python is installed, you can use the package manager `pip` to install Jupyter Notebook. Open your terminal or command prompt and run the following command:
   ```shell
   pip install jupyter notebook
   ```

3. Launch Jupyter Notebook: After the installation is complete, you can start Jupyter Notebook by running the following command in your terminal or command prompt:
    ```shell
    jupyter notebook
    ```

This will open Jupyter Notebook in your default web browser.

For more detailed instructions on installing Jupyter Notebook, you can refer to the [official documentation](https://jupyter.org/install.html).

## Usage

To run the Jupyter notebooks and reproduce the visualizations, follow these steps:

1. Clone the repository to your local machine or download the project files.

2. Open Jupyter Notebook by running the following command in your terminal or command prompt:

   ```shell
   jupyter notebook
   ```

3. In the Jupyter Notebook interface, navigate to the directory where you saved the project files.

4. Open the Jupyter notebook [index.ipynb](src/index.ipynb) file and execute the cells to run the code and generate the visualizations.

Feel free to explore the Jupyter notebooks, modify the code, and experiment with different datasets or parameters.


## Directory Structure

The project directory structure is as follows:

```bash
├── data-visualizations/     # Contains visualization media files
│   ├── 1.jpeg                  # First data visualization
│   ├── 2.jpeg                  # Second data visualization
│   ├── 3.png                   # Third data visualization
│   ├── 4.mp4                   # Fourth data visualization
├── presentations/           # Contains presentation files
│   ├── presentation.mp4        # Video presentation file
├── src/                     # Contains source code
|   ├── datasets/               # Contains dataset files
|   │   ├── employees.csv           # Dataset file for employee data
|   │   ├── landscape.csv           # Dataset file for landscape data
|   │   └── calendar.csv            # Dataset file 
│   └── index.ipynb             # Project notebook which contains code
├── README.md                # Project readme file
└── report.pdf               # Project report
```
## Attribution

This project would not have been possible without the invaluable contributions and guidance of the following individuals and resources:

- **Professor's Lecture and Guidance**: A special acknowledgment goes to professor Terrence Tricco for his expert knowledge, valuable insights, and guidance throughout the project. His lectures and instructions have played a significant role in shaping this work.

- **Documentation and Resources**: The project has benefited from various documentation sources and resources, including:
  - [Pandas](https://pandas.pydata.org) - The documentation and examples provided by the Pandas library were instrumental in data processing and manipulation.
  - [Matplotlib](https://matplotlib.org) - The Matplotlib documentation and gallery have been a valuable resource for creating visualizations.
  - [Seaborn](https://seaborn.pydata.org) - The Seaborn documentation has provided insights into advanced visualization techniques.
  - [Stack Overflow](https://stackoverflow.com) - The Stack Overflow community's questions and answers have been immensely helpful in troubleshooting and finding solutions to coding challenges.
