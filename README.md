# Data Scientist

## About me

I am a Data Scientist with a solid background in quantitative methods and statistical analysis, focused on extracting knowledge from data to drive strategic decision-making. I am currently pursuing two master’s degrees at the University of Buenos Aires: Management and Data Analysis in Organizations, and Data Mining, enhancing my skills in data science, advanced analysis, and process automation.

I have experience using industry-standard tools such as Python, R, SQL, Plotly, and Power BI, applying them to develop analytical solutions, automate workflows, and create effective visualizations.

I am passionate about solving complex problems, optimizing processes, and generating value through advanced analysis techniques and clear communication of results. My goal is to transform data into strategic insights to improve efficiency and decision-making within organizations.

### Technical Skills: ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54), ![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white), ![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white), ![R](https://img.shields.io/badge/r-%23276DC3.svg?style=for-the-badge&logo=r&logoColor=white), ![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white),![Power Bi](https://img.shields.io/badge/power_bi-F2C811?style=for-the-badge&logo=powerbi&logoColor=black), ![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)

<!-- PARA HACER QUE EL LINK ABRA EN OTRA PESTAÑA
<a href="https://www.linkedin.com/in/jesus-alberto-ochoa/" target="_blank">
  <img src="https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
</a>-->

### Contact: [![LinkedIn](https://img.shields.io/badge/linkedin-%23295F98.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jesus-alberto-ochoa/)

* * *

# Projects


## Stats Explorer Summary NBA

The world of basketball has evolved over the years, with more specialized training, players preparing at an earlier age, and an increasingly competitive level of play. Therefore, it is essential for teams and talent scouts to stay aligned with the offensive and defensive trends showcased by the world's top teams and players. This app will enable users to identify trends changes and analyze players' performance across different seasons, while also facilitating high-level comparisons and groupings based on their respective statistics.

#### [Link-App](https://nbastats-summary.onrender.com/)

### Key Questions

- How has the percentage of shot attempts by area changed over the seasons?
- How have teams evolved in their shot selection?
- How is the impact of players distributed based on their age?
- How have shooting percentages evolved by player position across different seasons?

### Technologies and Methodology

1. Web Scraper: Initially, the goal was to gather as much information as possible about NBA players and teams across all seasons. Using ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) and the bs4 module, data was extracted from the official NBA website to collect statistics deemed relevant for building the project’s outputs and models.

2. Data Storage and Management: To store the data extracted from the website, ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) was used to tabulate the information, enabling better management and manipulation of the data thanks to the comprehensive methods provided by this library. Currently, the extracted data is temporarily stored in ![Microsoft Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white) files. However, a database is being designed to enable more professional storage and easier access to the collected information.

4. Application and Visualization of Data: To create an application accessible to anyone, the Dash ![Plotly](https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white) module was used. This framework allows the development of robust and scalable web applications, enabling continuous improvements in both aesthetics and performance.

5. Version Controller: To maintain a changelog and implement a version control system, Git was used through GitHub Desktop. This approach optimizes the application of changes and facilitates code corrections.

### Next Steps

1. Automating the process of information extraction and loading into a suitable database management system.
2. Implement more statistics to compare the different eras for both teams and players.
3. Create the following models:
   * A model that allows to classify players into categories based on their performance in order to make use of this information criteria at the time of giving any of these labels to a player.
   * A model that can estimate the number of victories that a team can obtain according to the statistics that it obtains in different rules of the game.

**Explore more details and the project code in the [complete repository](https://github.com/jarof13/AppNBA.git).**
