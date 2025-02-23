

# Revenue Insights of a Hotel Chain

### Dashboard Link :https://drive.google.com/drive/folders/1pGkvVIdL39AzP68ECEv49BLgwKJg_r_M?usp=sharing

## Problem Statement

This dashboard is designed to help hotel management gain a deeper understanding of their customers. Various key performance indicators (KPIs) have been incorporated to provide comprehensive insights into their business. Some of the extensively used metrics in the hospitality industry included in the dashboard are Revenue Per Available Room (RevPAR), Average Daily Rate (ADR), Daily Sales Revenue Net (DSRN), Daily Booking Revenue Net (DBRN), Daily Unique Room Nights (DURN), Realization Percentage, and Occupancy Percentage. Several graphs and tooltips have been added to facilitate the analysis of week-over-week (WoW) changes across different aspects. Filters based on cities, months, and weeks have also been incorporated to enhance the user experience.

# Report Snapshot (Power BI DESKTOP)
![Screenshot 2025-01-12 115832](https://github.com/user-attachments/assets/d2c18aca-256f-491c-be26-5e74f66cd0f7)

### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & perform the data transformation.In order to create a schema in the next step, create fact tables and dimension tables. Delete the day type from dim_date as in hotel business weekends are different from the regular norms.
- Step 3 : Now we move to data modelling where we establish relationship. In this project we are going to follow the star schema.After connecting, verify your relationship to avoid any discrepancies. ![Screenshot 2025-01-12 123422](https://github.com/user-attachments/assets/cf030ef9-6285-48c3-8084-0b0064302d67)


- Step 4 : Build several key metrics in DAX. Create calculated colum for day_type and then add all the measures.
- Step 5 : Create a key_measures table. Add various measures like Revenue, REvPar, ADR, occupancy%, DSRN, DURN, DBRN to name a few.
- Step 6 : After creating all the mesures, now we will start with the dashboarding. 
- Step 7 : Create a table. Add the following colums :property_id, property_name, city, Revenue, REvPar, Occupancy%, ADR, DSRN, DURN, DBRN, REalisation %, Cancellation %, Average Rating
- Step 8 :Several formating s have been done to the table such as removing decimals, adding horizontal graph to make it more user friendly.
- Step 9 : Add various filters such as city, date, week, month, room type .Use the slicer to create these filters for the dashboard.
           
- Step 10 :  Now we add a few cards for Revenue ,RevPar, DSRN, Occupancy%, ADR and Realisation. A percentage change at the bottom of each card is attached which shows WoW changes.

- Step 11 : In order to make the dashboard more interactive, we add tooltips which while we hover over the card presents the trend in graph for easy visualization.Some of the tool tips are:

  (a) Revenue ![Revenue_TT](https://github.com/user-attachments/assets/26272c2c-8325-44a2-9427-cf0f37bda9c5)

  (b) RevPar ![RevPar_TT](https://github.com/user-attachments/assets/0f535aff-8336-4748-bbb8-f518152801ac)

  
  (c) DSRN
  
  (d) occupancy% ![Occupancy_TT](https://github.com/user-attachments/assets/ff480451-1be4-4fe5-b828-3fdca14c0f14)

  
  (e) ADRN
  
  (f) Realisation ![Realisation_TT](https://github.com/user-attachments/assets/5ae6fbaa-4e01-4b1b-b96f-3ab48e1b4a45)




- Step 12 : Create a Donut chart. Add category to the legend and add occupancy percentage to values.
- Step 13 : Add two ther graphs for more information.
- Step 14 : Add section and depth in the dashboard for a better user experience.

