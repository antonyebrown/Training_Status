# Unit Training Status Dashboard

This Jupityr notebook will create a table of a unit's training status from from raw .csv exports. These files were a bit tricky to wrangle: Not all students had attempted the same courses, and many courses have different due dates (1, 2, or 3 years from last completion).

The goal is to have a semi-automated process that works from .csv files that the unit training manager can download. Then, the analyst simply has to drop the files into the appropriate folder on a weekly (or any timeframe) basis, and run this workbook. The resulting table is then linked to Tableau as an interactive dashboard for visualization, where the most important courses are tracked.

Note: All names used are fictitious.

	
The Tableau dashboard can be found [here](https://public.tableau.com/views/UnitTrainingStatus/UnitTrainingStatus?:language=en-US&:display_count=n&:origin=viz_share_link "Unit Training Status").

### Skills used:
	
**Python**
* Data cleaning
* Data blending

**Tableau**
* Data visualization
* Interactive dashboard
* KPI identification and indication
* Data segmentation and aggregation via calculated fields
