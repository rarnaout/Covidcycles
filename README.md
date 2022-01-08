# Plotting COVID-19 Deaths vs. Cases

Please see the covid_deaths_vs_cases.ipynb

![](south_africa_010822.png)

For most of the COVID-19 pandemic, the daily focus has been on the number of cases. 

This still seems to be true as the omicron wave hits.

But omicron on the whole has been much milder. For those who are recently doubly or triple vaccinated and/or recently infected who are free from underlying comorbidities (of which the list is long), the risk of death is very small. The primary risk of this phase of the pandemic is for those not in the above groups getting sick all at once, overwhelming available beds, while the healthcare workforce is itself depleted as workers quarantine or are at home suffering (usually mild) symptoms.

I thought an interesting way to visualize differences in the various peaks would be by plotting deaths as a function of cases.

The below function, `plot_deaths_vs_cases`, does this.

It is not the prettiest, but it does the job.

Among (many) possible improvements:

- label the peaks dynamically
- make sure labels are always within axes

The comments below are as of January 8, 2022.

-- Ramy Arnaout, MD, DPhil
