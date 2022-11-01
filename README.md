# Nigeria-Disease-Death-Analysis by Bright Daniel
## Dataset Description
> The dataset used for this analysis was extracted from https://www.kaggle.com/datasets/iamsouravbanerjee/cause-of-deaths-around-the-world/download?datasetVersionNumber=2. It contains countries, their codes,various diseases and the number of people killed by these diseases from 1990-2020. For this work,the focus was on Nigerian diseases and the number of deaths.
## Aim
> To giving insights on the top 5 diseases with highest death rate in Nigeria.
## Workings
>After the dataset was downloaded from the link above,Python-pandas was used to extract rows containing Nigeria since the analysis was to focus on Nigeria. Matplotlib was used to analytically visualize the number of deaths caused by these diseases, then the top five most killer diseases where noted and used for creating dashboards on Tableau.
## Summary of Findings
1. The top five most diseases based on the number of deaths in descending order are ; Diarrheal diseases, Malaria, Low respiratory infections, Neonatal disorder and Cardiovascular diseases.
2. Diarrheal has its highest killings in 1991(297,403 people) and lowest in 2019(181,138). There is a decline in number of deaths caused by this disease over the years. For Malaria, its highest kill was in 2008(280,604) and lowest in 1990(248,419). From 1990 to 2008 there was a constant rise in the number of deaths caused by Malaria, a rapid decrease occure from 2009 to 2017 before  a slight rise again from 2018 to 2020.
Lower respiratory infections killed more people in 2002(216,744) and less in 1990(169,472).From 1990-2002 it shows an increase in the number of deaths before a slight fall from 2003-2012 before it become constant. The last three years there has been a drop in the number of killings by LRD. For Neonatal disorder, it shows a constant increase over the years from 1990 to 2013 with highest killings in 2013(204,573) and a decrease from 2014 to 2019.
3. Comparison in pairs shows that the death rate by diarrheal has been controlled over the years compared to malaria. In 2005 Malaria and Diarrheal killed almost the same number of people. In 2008 Neonatal disorder and LRD killed almost the same number of people with Neontal disorder showing persistent rise compared to LFC.
