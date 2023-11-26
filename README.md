# LP1_Project-1
# LP_1_Project, Titled:
Analysis On Indian Startup Ecosystem From 2018-2021
 
This project is to analyze the funding data of Indian start-ups from the years 2018 to 2021 to gain a deep understanding of the financial landscape within the Indian start-up ecosystem.
 
## Table of Contents
 
- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)
 
## Overview
 
The objective for this project is to analyze the funding data of Indian start-ups from the years 2018 to 2021 to gain a deep understanding of the financial landscape within the Indian start-up ecosystem. The primary focus is to identify the sectors or industries that have consistently demonstrated significant growth potential and attractiveness for investments. This analysis will serve as the foundation for making strategic decisions regarding entry or expansion into the Indian start-up ecosystem, ensuring that resources are directed towards the most promising areas that offer the best prospects for success and return on investment.
 
## Features
 
- Data Exploration:
 
Perform in-depth exploration of the start-up funding dataset, gaining a comprehensive understanding of available information.
 
- Time-Series Analysis:
 
Conduct a time-series analysis to observe trends and patterns in start-up funding over the four-year period from 2018 to 2021.
 
- Sector-Specific Insights:
 
Provide insights into funding patterns within different sectors, identifying those that have received the most significant investments. (Ideally be able to capture the top ten sectors with the highest funding activity)
 
 
- Startup Count Trends:
 
Illustrate annual trends in the number of start-ups funded, offering insights into the overall growth or contraction of the start-up ecosystem.
 
- Outlier Identification:
 
Identify and visualize outliers in funding amounts, helping to pinpoint companies that have received exceptionally high funding compared to the rest.
 
- Visualizations for Quick Insights:
 
Generate interactive and visually appealing charts and graphs for easy interpretation of complex funding data.
 
- Hypothesis Testing:
 
Perform hypothesis testing to validate assumptions about changes or variations in the start-up funding landscape.
 
- Top Sectors Ranking:
 
Rank sectors based on the total funding received, enabling stakeholders to prioritize investment opportunities.
 
- Strategic Decision Support:
 
Provide actionable insights for strategic decision-making, aiding investors, entrepreneurs, and stakeholders in making informed choices for their involvement in the start-up ecosystem.
 
 
- User-Friendly Documentation:
 
Provide clear and concise documentation to guide users on how to interact with the project code, run analyses, and interpret results.
 
- Statistical Analysis:
 
Incorporate statistical methods for deeper analysis, including t-tests, ANOVA, and other relevant tests to validate hypotheses and draw meaningful conclusions.
 
 
## Installation
 
This is a sample guide on how to install or set up your project locally.
```bash
# Example installation commands
git clone https://github.com/your-username/your-project.git
cd your-project
pip install pyodbc
pip install dotenv
pip install numpy,seaborn, matplotlib.pyplot
 
 
## Usage
 
### Prerequisites
 
Before you get started, ensure that you have the following installed:
 
- Python (version x.x.x)
- Jupyter Notebook (optional for interactive exploration)
 
### Installation
 
1. Clone the repository:
 
   ```bash
   git clone https://github.com/your-username/your-project.git
 
 
##Dependencies
-The following dependencies are required to run this project:
 
- [Python](https://www.python.org/) (version x.x.x)
- [Jupyter Notebook](https://jupyter.org/) (optional for interactive exploration)
 
### Python Libraries
 
- [pandas](https://pandas.pydata.org/) - Data manipulation and analysis
- [matplotlib](https://matplotlib.org/) - Data visualization
- [seaborn](https://seaborn.pydata.org/) - Statistical data visualization
- [scipy](https://www.scipy.org/) - Scientific computing tools
 
 
##Contributing
Fork the Repository:How users can create their own fork of the repository to make changes.
 
bash
Copy code
# Fork the repository on GitHub
Clone the Repository: This is a guide to my users on how to clone their forked repository to their local machine.
 
bash
Copy code
git clone https://github.com/your-username/your-repository.git
Create a Branch: Always create a new branch for your changes
 
bash
Copy code
git checkout -b feature/new-feature
Make Changes: Explained process of making changes and additions to the codebase.
 
Commit Changes: Guide users on how to commit their changes locally.
 
bash
Copy code
git commit -m "Add new feature"
Push Changes:How to push your changes to your forked repository.
 
bash
Copy code
git push origin feature/new-feature
Create a Pull Request: These are steps for creating a pull request to propose changes to the original repository.
 
Code Review: Outline the process for code review and collaboration.
 
markdown
Copy code
 
### Code Review Guidelines
 
- Ensure code follows the project's coding standards.
- Include tests if applicable.
- Clearly document new features or changes in the project's documentation.
- Respond to feedback and iterate on changes.
Reporting Issues: Encourage users to report issues, bugs, or suggest improvements by creating a GitHub issue.
 
markdown
Copy code
 
## Reporting Issues
 
If you encounter any issues or have suggestions for improvements, please open a GitHub issue
 
 
##License
 
This project is licensed under the MIT  License


REPORT FINDINGS:
1. It is evident that the funding is higher in 2020 and 2021. This could be linked to the pandemic that was experienced in these years (Covid-19). 
2.In 2018 the funding that is quite prevalent is Angel, debt financing and Equity at an almost equal share. This means that the startup ecosystem was quite balanced, with not much of start ups struggling.
   In 2019, there is a good share of seed and series funding which is more of a second or third etc round of funding. this could point towards the start ups scaling up and thus the need for more funding. 
   In 2020, we see the Debt financing creeping back in indicative of a struggle in the start ups which could be attributed to the pandemic that was being faced.
3. The trend shows a general increase in funding from 2019 onwards. This could be attributed to the effects of Covid-19. Also, notably we had very few funded companies in 2019, a slight drop from the companies funded in 2018. this could have been attributed to the fact that the funding in 2019 was more of a seed and series(repeat funding to grow the business for shares.)
4. In 2018, it's evident that the highest funding was for equity. 
For 2019 and 2020, there was no direct corelation between the outlier funding and the stage of funding. there was also no direct relation to the sectors that were funded.

In 2021, the outlier was in Fintech. This can be attributed to the need to embrace technology during the covid peak period. This involved embracing remote delivery of tasks amongst other tech-related demands.
