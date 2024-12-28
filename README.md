# Space Mission Analysis

This repository contains an analysis of space mission data with a focus on the Cold War space race, launch statistics, mission success and failure rates, and the dominance of space organizations over time.

## Project Overview

This project explores historical space mission data to answer key questions about the competition between major space powers (especially the USA and USSR) and the performance of different space organizations. Using Python and various visualization libraries, the project provides insights into the number of space launches, mission failures, and the evolving dominance of space organizations, including a special focus on the Cold War period (USA vs USSR).

## Data

The analysis uses a comprehensive dataset of space missions, including:

- Launch Year
- Organisation
- Country
- Mission Status (Success or Failure)
- Location of launch

The dataset spans several decades, with a focus on the Cold War era and includes launches from countries like the USA, USSR, and former Soviet republics such as Kazakhstan.

## Key Insights and Visualizations

The following insights are explored and visualized in this project:

1. **Number of Launches Over Time by the Top 10 Organisations**  
   A line chart showing the number of space launches over time by the top 10 organizations involved in space exploration.

2. **USA vs USSR Total Launch Comparison**  
   A pie chart comparing the total number of space launches between the USA and USSR (including former Soviet republics like Kazakhstan).

3. **Total Launches Year-on-Year by the Two Superpowers (USA vs USSR)**  
   A line chart comparing the yearly number of launches by the USA and USSR.

4. **Total Number of Mission Failures Year-on-Year**  
   A line chart depicting the number of mission failures over the years.

5. **Percentage of Failures Over Time**  
   A line chart showing the percentage of mission failures over time, indicating how countries improved their launch success rates.

6. **Leading Country in Terms of Total Launches Each Year (Up to 2020)**  
   A chart showing which country led in terms of total launches each year.

7. **Leading Country in Terms of Successful Launches Each Year (Up to 2020)**  
   A similar chart showing which country had the highest number of successful launches each year.

8. **Year-on-Year Organisation with Most Launches**  
   A chart showing which organization performed the most launches each year, with a focus on dominance in the 1970s and 1980s as well as recent years (2018-2020).

9. **Comparison of Dominant Organisation in the 1970s/1980s vs 2018-2020**  
   A comparison of which organization was dominant during the Cold War era (1970s-1980s) versus the years 2018-2020.

## Setup and Requirements

To run this project locally, you need to have Python 3.x and the following libraries installed:

- pandas
- numpy
- plotly
- matplotlib
- seaborn

You can install the required libraries using `pip`:

```bash
pip install pandas numpy plotly matplotlib seaborn
```

## How to Run

1. Clone the repository to your local machine:

```bash
git clone https://github.com/Prathamesh326/Space-Mission-Analaysis.git
```

2. Navigate to the project directory:

```bash
cd Space-Mission-Analaysis
```

3. Run the analysis script (`space_mission_analysis.py`) in your preferred Python environment. This script contains all the data processing, analysis, and plotting commands.

```bash
python space_mission_analysis.py
```

4. The visualizations will appear in your browser or an interactive plot window.

## Contributions

Feel free to fork the repository and contribute to improving the analysis or adding new features. If you have any suggestions or bug reports, please create an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- The dataset used in this project is publicly available and includes contributions from various space agencies and organizations.

- Special thanks to the Python data science community for the powerful libraries (pandas, numpy, plotly, etc.) that make data analysis and visualization possible.

```

This README provides a comprehensive overview of the Space Mission Analysis project, including setup instructions, the types of visualizations and analyses it generates, and the tools required to run it. You can modify or extend it depending on the specifics of your project.
