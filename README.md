Project Title:
Machine learning based impact factors analysis for covid-19.

Understanding:
The COVID pandemic was one of the worst ever and completely upended the society. COVID-19 has been a hot topic, and numerous studies have already been conducted on it. This project examines a wide range of factors that may have an impact on COVID instances and fatalities and also forecasting the COVID cases and fatalities using time series machine learning models.

Data Understanding
It is essential to start the process by gathering an accurate and trustworthy dataset, which is the first stage. Finding a high-quality dataset might be challenging, but doing so is crucial since it improves the validity of the research and facilitates wise decision-making while analysing the dataset.
Our Word in Data and Visual Crossing are two official sources from which the datasets were gathered for this study. A well-known organization's website called "Our World in Data" offers accurate information on a range of international issues.

Results:

ARIMA model outperformed Fb-Prophet model for both COVID cases and COVID deaths
Technologies Used
Google Colab was used for this project.

Approach
Data was first cleaned by removing null values and Outliers. The z-score approach, a statistical tool, is used to locate and treat outliers. With this approach, the standard deviations of data point departures from the mean are evaluated.
Conducted Pearson correlation analysis on COVID datasets from multiple countries to assess relationships between environmental factors (temperature, dew point, humidity, windspeed) and COVID metrics (cases, fatalities).
Explored the influence of various factors (population density, poverty levels, handwashing facilities, vaccination status) on COVID spread and impact across different countries.
Highlighted findings showcasing minimal impact of climatic factors, subtle associations of poverty and hygiene facilities with case numbers, and the significant correlation between higher vaccination rates and reduced COVID deaths.
Then the data was fed into two time series models: ARIMA and Fb-Prophet. The dataset was separated country-wise and then fed into this model. Then, the performance of these models was compared in order to determine the best model amongst them.

Status of the project: The project Is completed.

