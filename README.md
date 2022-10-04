[![MIT License](https://img.shields.io/apm/l/atomic-design-ui.svg?)](https://github.com/tterb/atomic-design-ui/blob/master/LICENSEs)
![contributors](https://img.shields.io/github/contributors/TharunKumarReddy5/data-512-homework_1.svg)
![codesize](https://img.shields.io/github/languages/code-size/TharunKumarReddy5/data-512-homework_1.svg) 
![pullrequests](https://img.shields.io/github/issues-pr/TharunKumarReddy5/data-512-homework_1.svg) 
![closedpullrequests](https://img.shields.io/github/issues-pr-closed-raw/TharunKumarReddy5/data-512-homework_1.svg)

# data-512-homework_1
DATA 512 Human Centered Data Science Homework 1
Homework 1 for DATA 512 Human Centered Data Science course at the University of Washington - Masters in Data Science program

# Professionalism & Reproducibility : Goal

data-512-homework_1 project is an analysis exercise with primary goal to learn and incorporate the best practices for project documentation, as outlined in "Assessing Reproducibility" and "The Basic Reproducible Workflow Template" from The Practice of Reproducible Research.

## Datasource Information

The data for this project is extracted from the Pageviews API. The Pageviews API (documentation, endpoint) provides access to desktop, mobile web, and mobile app traffic data from July 2015 through the previous complete month.Leveraging the API, I collected the pageviews information using a subset of Wikipedia article pages. Please find below the subset of the English Wikipedia that represents a large number of dinosaur related articles.

 - [Pageviews API Endpoint](https://wikimedia.org/api/rest_v1/#!/Pageviews_data/get_metrics_pageviews_aggregate_project_access_agent_granularity_start_end)
 - [Pageviews API Documentation](https://wikitech.wikimedia.org/wiki/Analytics/AQS/Pageviews)
 - [Wikimedia Foundation REST API terms of use](https://www.mediawiki.org/wiki/REST_API#Terms_and_conditions)
 - [Dinosaur articles](https://docs.google.com/spreadsheets/d/1zfBNKsuWOFVFTOGK8qnTr2DmHkYK4mAACBKk1sHLt_k/edit?usp=sharing)

## Dependencies

Install the dependencies from the requirements.txt file using

    python -m pip install -r requirements.txt

## Issues and Special Considerations

The code has embedded exception handling to cover and highlight the articles for which we are not able to pull the page views information. As of now we are able to pull the information for all the dinosaur articles. Check for the comments in the code to debug the exceptions. 

## Repository Structure:
Here are the main folders in our github data-512-homework_1 repository:
```bash
.
├── DATA 512 Homework 1 Tharun.ipynb
├── README.md
├── LICENSE
├── dinosaur_genera.cleaned.SEPT.2022.xlsx
├── dinosaurs_all.xlsx
├── json
│   ├── dino_monthly_cumulative_201507-202209.json
│   ├── dino_monthly_desktop_201507-202209.json
│   └── dino_monthly_mobile_201507-202209.json
├── plots
│   ├── max_min_average_views.png
│   ├── top_10_peak_page_views.png
│   └── articles_with_fewest_months_data.png
├── requirements.txt
```

## Screenshots

Examples of outputs generated by the functions

- Screenshot of plot 1:

[Image1](https://github.com/TharunKumarReddy5/data-512-homework_1/blob/main/plots/max_min_average_views.png)
![Alt text](https://github.com/TharunKumarReddy5/data-512-homework_1/blob/main/plots/max_min_average_views.png "Articles with fewest Months of Data")

- Screenshot of plot 2:

[Image2](https://github.com/TharunKumarReddy5/data-512-homework_1/blob/main/plots/top_10_peak_page_views.png)
![Alt text](https://github.com/TharunKumarReddy5/data-512-homework_1/blob/main/plots/top_10_peak_page_views.png "ML Pipeline Hyperparameter Diagram")

- Screenshot of plot 3:

[Image3](https://github.com/TharunKumarReddy5/data-512-homework_1/tree/main/plots/articles_with_fewest_months_data.png)
![Alt text](https://github.com/TharunKumarReddy5/data-512-homework_1/blob/main/plots/articles_with_fewest_months_data.png "Articles with fewest Months of Data")

## Code Style

Languages used: Python
Coding Style:
    - PEP 8
    - Docstrings

Following sofware design principles have been considered while packaging MLPA:

- Modular design
    - *'Somewhat General Purpose'* module
    - Deep Modules
    - Separation of Concerns
- Reusability/Extensibility
- Intuitable
- Exception Handling

## Authors
- [Tharun Kumar Reddy Karasani](https://github.com/TharunKumarReddy5)

![GitHub Contributors Image](https://contrib.rocks/image?repo=TharunKumarReddy5/data-512-homework_1)

## Contribute

This project is an open-source project- open to the Python user community for contribution.
