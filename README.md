# Introduction 
This project aims to contain all notebooks and files created for 2023 global analytics project ***Data To Actionable Insights (D2AI)***.
D2AI is an intiative that aims to keep transforming ABI through deep understanding of its consumer data. This project is a sequence for Close the Loop (2022).

# Getting Started
Start up steps:
1.	Clone this repository and install all dependencies on Vertex AI interface or via command prompt.
2.	Pay attention to always keep the last version locally before trying to push changes.
3.	When creating new analysis cases (occasion), please follow structure below:

            ├── Occasion 1
            │   ├── Country A
            │   │   ├── Dataset Files Folder
            │   │   │    ├── dataset files, ...
            │   │   ├── Notebook1 (d2ai_country_occasion_case-name-1.ipynb)
            │   │   ├── Notebook2 (d2ai_country_occasion_case-name-2.ipynb)
            │   ├── Country B
            │   │   ├── Dataset Files Folder
            │   │   │    ├── dataset files, ...
            │   │   ├── Notebook1 (d2ai_country_occasion_case-name-1.ipynb)
            ├── Occasion 2
            │   ├── General Dataset
            │   │   ├── dataset files
            │   ├── Country A
            │   │   ├── Notebook1 (d2ai_country_case-name-1.ipynb)
            │   ├── Country B
            │   │   ├── Notebook1 (d2ai_country_case-name-1.ipynb)
            ├── No occasion
            │   ├── Country A
            │   │   ├── Dataset Files Folder
            │   │   │    ├── dataset files, ...
            │   │   ├── Notebook1 (d2ai_country_case-name-1.ipynb)
            │
            └── .gitignore



# Build and Test
To run the codes, just start a VM on Vertex Ai or another cloud service. Synchronize your jupyter lab with git, open the right notebook and start running or coding.

# Contribute
Please always follow coding standards and try to always leave the code better than you found it before you started to modify it.
