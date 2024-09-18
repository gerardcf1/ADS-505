# Final Team Project: Marketing Strategy Evaluation for New Menu Item

## Project Overview

This project aims to evaluate the effectiveness of three different marketing campaigns for a new menu item introduced by a fast-food chain. Using A/B testing, we will determine which promotion has the greatest impact on sales across various market locations. Our analysis will involve data cleaning, pre-processing, exploratory data analysis (EDA), and the application of data science methods using Python to derive actionable insights.

## Dataset

The dataset for this project includes the following columns:

- **MarketID**: Unique identifier for each market.
- **MarketSize**: Size of the market area based on sales volume.
- **LocationID**: Unique identifier for each store location.
- **AgeOfStore**: Age of the store in years.
- **Promotion**: Type of promotion used (one of three different promotions).
- **Week**: Week number during which the promotion was active (up to 4 weeks).
- **SalesInThousands**: Sales amount for the specific store location, promotion, and week.

### Data Source

- [Dataset Source](https://rpubs.com/ksdwivedy/finalRProject)
- Hands-On Data Science for Marketing book by Yoon Hyup Hwang
- Image by [Shaafi](https://unsplash.com/@shaafi) on Unsplash
- IBM Watson Analytics community

## Project Goals

1. **Problem Statement**: Determine which of the three marketing campaigns is most effective in increasing sales of the new menu item.
2. **Analysis Objectives**:
   - Conduct Exploratory Data Analysis (EDA) to understand data characteristics.
   - Perform data cleaning and pre-processing.
   - Implement data splitting for training, validation, and testing.
   - Build and evaluate models to identify the best-performing marketing strategy.
   - Provide business recommendations based on the findings.

## Project Deliverables

- **GitHub Repository**: The repository will contain all project files, including the Jupyter notebooks, data, and any scripts used for the analysis.
- **Technical Notebook**: A Jupyter notebook documenting the full analysis, including code, visualizations, and interpretations of results.
- **Video Presentation**: A 15-20 minute recorded video presentation covering both technical aspects (targeted at peer data scientists) and non-technical business recommendations (targeted at executives).
- **Business Brief**: A concise document outlining the project's objectives, findings, and recommendations.
- **Executive Summary Presentation**: A 6-slide presentation designed for a non-technical audience, summarizing the data story and key recommendations.

## Project Timeline

- **Module 2**: Team formation.
- **Module 3**: Dataset selection and initial project setup.
- **Module 6**: Submission of all deliverables, including the video presentation, business brief, technical notebook, and executive summary.

## Technical Implementation

### Tools and Libraries

- Python (Jupyter Notebooks)
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, and others as required.

### Project Structure

```plaintext
- /data: Contains raw and processed datasets.
- /notebooks: Jupyter notebooks for EDA, modeling, and analysis.
- /scripts: Python scripts used for data cleaning, processing, and modeling.
- /presentation: Slide decks for the executive summary and business brief.
- README.md: Project overview and guide.
