# Video Games and Academic Performance

## Description
This project explore how many hours of videogames played per week results in the best grades. Keep in mind that this does not imply causation. Furthermore, I looked at the relationship between total gaming time reported and grades to see the relationship from quite few hours of videogames played to a lot of hours played. 

## Data and Visualizations
The total observations in this dataset is 8000. Originally gaming was defined as hours per day, so I multiplied it by seven for the weekly estimates. 

The project uses Python and matplotlib to create multiple different visualizations:
- Scatterplot: The first attempt, that turned our unreadable due to individual datapoints.
- Hexbin plot: Helps with displaying concentrations instead of singular datapoints. 
- Box plot: Is used as a simplified way of showing that the more video games students report playing per week, the lower their average grades are. Confirming the Hexbin plot.
- I used colorblind friendly colors inspired by https://www.simplifiedsciencepublishing.com/resources/best-color-palettes-for-scientific-figures-and-data-visualizations. 

## Preliminary Conclusion
The visualizations show that between 0-10 hours of videogames per week is associated with the best grades. Furthermore, the higher the amount of reported video game time, the lower the average grades. 

## How to Use This Project
Clone or download the GitHub repository. https://github.com/VetleBersaas/Gaming-Grades-Gig/tree/main
Open the project folder in Visual Studio Code.
Ensure Python and the required libraries are installed: pandas, matplotlib, and jupyter.
Place Gaming_Academic_Performance_updated.csv inside a folder named data.
Open gaming_grades.ipynb in VS Code.
Select a Python kernel and run the notebook cells in order.

## Credits
Project author: Vetle Bersaas

Programming language: Python

Libraries: pandas, Matplotlib, and Jupyter

AI assistance: ChatGPT was used to help explain code, fix and update authors code, troubleshoot errors and draft documentation.

Dataset: Gaming_Academic_Performance_updated.csv - this was taken form https://www.kaggle.com/datasets/aiexplorer77/gaming-vs-academic-performance?resource=download

## License
This project's code is licensed under the GNU General Public License v3.0 (GPL-3.0).
