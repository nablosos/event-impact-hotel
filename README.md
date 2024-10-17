**Event Impact Analysis on Hotel Performance Metrics**

## Objective:

*   Analyse the impact of events on hotel performance metrics using the provided datasets. Candidates are expected to explore the relationship between event characteristics (e.g., type, location, expected attendance) and key hotel performance indicators (occupancy rates, ARR, and number of guests). Based on the insights gathered, develop a predictive model that forecasts future hotel performance metrics, leveraging information on upcoming events.

##   

## Dataset:

**Events dataset:** Contains information about different events (e.g., concerts, exhibitions, festivals) including date, type, location, and expected attendance.

| Column | Description |
| --- | --- |
| Event | Name of the event |
| Event parent category | Broad category of the event (e.g., international, homegrown) |
| Event Vertical | The industry or vertical to which the event belongs (e.g., sports, entertainment) |
| Event Category | Specific event category (e.g., international sports events) |
| Business Model | The business model applied to the event (e.g., MIRPAR, PAR) |
| Strategic Project | Indicates if the project is strategic or non-strategic |
| Start Date | Start date of the event (DD/MM/YYYY) |
| End Date | End date of the event (DD/MM/YYYY) |
| Location | The location where the event takes place |
| Attendees | The number of attendees for the event |
| Cost | The cost associated with the event (in local currency) |

**Hotels performance dataset:** Includes hotel performance metrics such as occupancy rates, average daily rate (ADR), revenue per available room (RevPAR), and number of guests, segmented by location and time.

| Column | Description |
| --- | --- |
| Date | Date of the record (DD/MM/YYYY) |
| ARR | Average room rate (per day) |
| Occupancy | Hotel occupancy rate (as a proportion of total capacity) |
| Total Guests | Total number of guests staying in the hotel |
| Domestic Guests | Number of domestic guests staying in the hotel |
| International Guests | Number of international guests staying in the hotel |

##   

## Deliverables:

1.  A Jupyter notebook (or equivalent) with clean, well-documented code that explains each step of the data analysis and model-building process.
2.  A report (in PDF or PowerPoint) summarizing:
    *   Data exploration and cleaning steps
    *   Key insights from the analysis of event impacts on hotel performance
    *   The approach and reasoning behind the chosen predictive model
    *   Recommendations based on the analysis and model results
3.  The trained predictive model along with evaluation metrics, such as accuracy, RMSE, or other relevant performance measures.

## Evaluation Criteria:

1.  Data cleaning and preprocessing:
    *   Effectiveness in handling missing or inconsistent data
    *   Thoughtful approach to feature engineering
2.  Deriving Insights from the analysis:
    *   Quality of insights drawn from exploring relationships between event data and hotel performance metrics
    *   Ability to derive actionable business recommendations
3.  Model justification and performance:
    *   Appropriateness of the predictive model selected for the task
    *   Accuracy and relevance of the model's performance based on evaluation metrics
    *   Clear explanation of why the model was chosen
4.  Communication and presentation:
    *   Clarity and organization of the report
    *   Ability to explain technical aspects to non-technical stakeholders
    *   Overall professionalism in the presentation of findings
5.  Bonus (Optional):
    *   Additional points for including a "what-if" analysis (e.g., simulating the impact of hypothetical events on hotel performance).
