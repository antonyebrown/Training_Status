# Unit Training Status Dashboard

Here, the client wanted an interactive dashboard that displayed the current status of the most important courses that their members have completed. I created a semi-automated process that works from raw .csv files that the unit training manager can download. Then, they simply have to drop the files into the appropriate folder on a weekly (or any timeframe) basis, and run the Jupityr notebook.

These files were a bit tricky to wrangle. Not all of the students had attempted the same courses, and many courses have different due dates (1, 2, or 3 years from last completion date). After cleaning the data, the resulting table is then linked to Tableau as an interactive dashboard for visualization and interaction.

Note: All names used are fictitious.

	
The Tableau dashboard can be found [here](https://public.tableau.com/app/profile/antony.brown/viz/UnitTrainingStatus/UnitTrainingStatus "Unit Training Status").

![Unit Training Dashboard](https://github.com/antonyebrown/Training_Status/blob/main/dashboard_pic.png?raw=true)

### Skills used:
	
**Python**
* Data cleaning
* Data blending

**Tableau**
* Data visualization
* Interactive dashboard
* KPI identification and indication
* Data segmentation and aggregation via calculated fields
