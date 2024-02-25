# Cincinnati-Health-Care-Centers
Conducted data analysis and visualization using Tableau to address research questions in healthcare service availability and costs in Cincinnati. Implemented interactive map visualizations to pinpoint health center locations and identify cost-effective healthcare options, achieving an accuracy rate of 85% in identifying budget-friendly hospitals.

HI 7072 FINAL PROJECT PROPOSAL
ESWAR RAO RAMINENI
Data Source Link: https://data.cincinnati-oh.gov/Thriving-Neighborhoods/Cincinnati-Health-Department-Health-CareCenters/v8yh-wpss/data
File Name: CincyHealthCenters.csv
Data:
For my research, I've chosen the "CincyHealthCenters.csv" dataset, which I've previously utilized in module 5. This dataset is
structured, containing both textual and numerical values. It includes geographic details like addresses, cities, states, latitude, and
longitude, along with statistical figures such as average lab fees and medical charges. These numeric values are crucial for
conducting data analysis. Moreover, the dataset also features a "Service Provided" column containing unstructured data in the
form of sentences. This presents an opportunity to employ text-mining techniques for data analysis. To enhance the dataset, I've
updated its origin source with three additional columns: average medical fee, lab fee, and admission, utilizing Google resources.
These added fields will facilitate a more detailed analysis to address the research questions at hand. Additionally, by extracting
the "Service Provided" column data into a text file, I've created an unstructured dataset. The selection of the
"CincyHealthCenters.csv" dataset allows me to explore both structured and unstructured data, enabling a comprehensive
investigation for this research.
Research Questions:
1. What types of healthcare services are predominantly available in Cincinnati?
Visualization Plan: Bar chart using ggplot in R and Tableau.
Description: This visualization will display the distribution of healthcare types on the x-axis and the frequency of these types
available in Cincinnati on the y-axis. Different healthcare types will be represented with distinct colors, providing a clear
overview of their prevalence.
2. Which neighborhoods have varying levels of nursing home availability and areas needing improvement?
Visualization Plan: Line chart showcasing neighborhood frequencies and bubble chart in tableau.
Description: The line chart will exhibit neighborhood frequencies on the x-axis and the presence or absence of nursing services
on the y-axis. Two lines will represent neighborhoods with and without nursing services, allowing for a comparison of areas
needing more nursing homes.
3. How can good healthcare hospitals with lower admission and medical costs be identified?
Visualization Plan: Geographic map pinpointing hospital locations.
Description: This visualization involves a geographic map that marks hospital locations and displays the type of services offered
along with admission and medical fees. This visual aid will assist in easily identifying areas with good healthcare options and
lower costs.
4. What are the most popular services provided by healthcare facilities in Cincinnati?
Visualization Plan: Word count visualization using R and Tableau.
Description: Utilizing the unstructured "Service Provided" column data, this visualization will present word count statistics. By
identifying high-frequency service terms, this visualization will effectively highlight the most sought-after healthcare services.
5. Is there a statistically significant correlation between geographic location and average lab fees in Cincinnati?
Visualization Plan: Scatter plot visualization using R.
Description: By using the geographic locations such as latitude and longitude we can plot the locations in graph and draw a
trendline for average lab fee for corresponding hospitals. Based on this we can find trendline and relationship between
locations.
6. How to identify the best budget hospital near to the patient?
HI 7072 FINAL PROJECT PROPOSAL
ESWAR RAO RAMINENI
MID: M15270716
Visualization Plan: Map visualization in R and tabular, map visualization in R.
Description: By using hospital locations and admission fee, lab fee and medical cost we can plot maps with pinpoint showcasing
the required values in labels and we can also table the data in tableau.
7. Find the statistics of health care with average admission fee, lab fee and medical cost and find which is the most expensive
treatment?
Visualization Plan: Side Bar in Tableau.
Description: By using the care type, measure values such as lab fee, admission fee and medical cost we can draw a side-by-side
bar chart in tableau, here we can group the data by care types. By doing this we can identify the most expensive care type in
Cincinnati.
Data Variables:
VARIABLE NAME DESCRIPTION DATA TYPE
HEALTH_CENTER Name of the healthcare center Text/String
HEALTH_CENTER_CODE Unique code for the healthcare center Text/String
ADDRESS Street address of the center Text/String
STREET_NAME Name of the street Text/String
SUFX Suffix for the street (if any) Text/String
CITY City where the center is located Text/String
STATE State where the center is situated Text/String
ZIPCODE Zip code of the location Text/Numeric
PHONE Contact phone number Text/String
CARE_TYPE Type of healthcare service provided Text/String
MONDAY_OPEN to FRIDAY_CLOSE Timings of the center for each day of the week Time/Text
SPECIAL_HOURS_NOTES Any special notes regarding operating hours Text/String
SERVICES_PROVIDED Description of services offered Text/String
CENTER_DESCRIPTION Description of the healthcare center Text/String
INSURANCE_ACCEPTED Accepted insurance types Text/String
TITLE_X_SERVICES Types of specialized services offered Text/String
NEIGHBORHOOD Neighborhood where the center is located Text/String
LATITUDE Geographic coordinate - Latitude Numeric
LONGITUDE Geographic coordinate - Longitude Numeric
ADULT to SAFE_PLACE Services available (Yes/No indicators) Boolean/Text
AVERAGE_MEDICAL_COST Average medical cost for Health care hospital Numeric
ADMISSION_FEE Admission fee for Health care hospital Numeric
AVERAGE_LAB_FEE Average lab fee for Health care hospital Numeric
