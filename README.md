# ds2023crime
public repo for group project. 

**branch testing - jimmy** nice

# pls read
i need to add you guys as collaborators, but in the mean time you could just clone the repo instead of creating a new branch.

also only refer to the optimaldraft notebook, the draft notebook is a scattered brain dump. dont use that please

**General Ideas for Dashboard**

Alluvial for Arrest, Domestic, and Crime Type

Pie Chart of crime types per year. Year is the interactive portion

Scatterplot, using long and lat. Plot the locations of a specific Crime.

Crimes on Holidays - Bar Plot, or maybe a grouped bar plot. idk. 

**Download Instructions for Data**
The Chicago Crime dataset is simply too large to be stored on GitHub. To download the version we're using for this project, go to 

https://data.cityofchicago.org/Public-Safety/Crimes-2001-to-Present/ijzp-q8t2/explore/query/SELECT%0A%20%20%60date%60%2C%0A%20%20%60block%60%2C%0A%20%20%60primary_type%60%2C%0A%20%20%60description%60%2C%0A%20%20%60location_description%60%2C%0A%20%20%60arrest%60%2C%0A%20%20%60domestic%60%2C%0A%20%20%60district%60%2C%0A%20%20%60fbi_code%60%2C%0A%20%20%60x_coordinate%60%2C%0A%20%20%60y_coordinate%60%2C%0A%20%20%60year%60%2C%0A%20%20%60latitude%60%2C%0A%20%20%60longitude%60%2C%0A%20%20%60id%60%0AWHERE%20%60year%60%20%3E%202022%0AORDER%20BY%20%60date%60%20DESC%20NULL%20FIRST/page/column_manager 

and export the data with the preset query
