## Florida Hacks with IBM Competition 
### Submission by Damian Ohienmhen
## <img src="./IBMGraphic.png" width = "230" height = "220" class="img-responsive" align = "left" alt="Florida"> <img> 

## Hackathon Overview

This challenge provided an oppourtunity to use the weatlh of data available in the public domain to address the effects of climate change. As sea water levels rise and global temperatures increase, it is important that we use all the available tools at our disposal to mitigate the worst effects of a changing climate. This challenge invites participants to use IBM Machine Learning/Artificial Intelligence tools to build solutions which address these problems.

### Challenge Statement #4 - Power Consumption

Florida has one of the largest per capita consumptions of energy in the United States. The bulk of this energy is drawn from fossil fuels leading to high carbon emissions. Currently there is a lack of public and private spending and initiatives in the Sunshine State for use of renewable energy resources such as solar and wind. 

Participants are invited to contribute to help develop applications for facilitating higher usages of renewable energy sources and optimize for efficient energy usage for all types of resources. 
 
How can we:
1. Analyze and target locations for renewable energy sources.
2. Optimize power generation to reduce overproduction.
3. Target and reduce areas of inefficient energy usage.



### Strategy and Implementation

Using the IBM Cloud Pak Data Solution and libraries available on the Notebook Platform, a detailed analysis of Florida's power consumption and renewable energy potential was carried out. Data sources such as consumable API from the National Solar Radiation Database (NSRDB) and Florida's Municipal Electric Association were used in the analysis. 

API Data was cleansed and re-formatted appropriately for the task. Major variables like Mean Direct Horizontal Irradiation (DHI), Mean Global Horizontal Irradiation (GHI) and Mean Direct Normal Irradiation were computed and used for our Machine Learning (ML) model. The K-Means Unsupervised Machine Learning Model was used to cluster the various variable points. The graphic of the resulting solution is shown below.

## <img src="./kmeans.png" width = "230" height = "220" class="img-responsive" align = "left" alt="Florida"> <img> 

The colored points represent the various major cities in Florida. Each of the 65 cities have now been classified across 3 different categories. They are described as follows:

1. Clusters in Purple - These points have the highest averages across each of the the variables under study. These points are recognized to have the greatest potential for both solar and wind generating assets.
2. Clusters in Light Green - These points show high means across each of the variables described in the analysis. They have been identified to have the 2nd best alternative for renewable energy assets.
3. Clusters in Red - These points show the least averages across each of the major data points under consideration. As a result, these areas have the least potential for renewable energy generation when compared to the other clusters.

Next, the question of overproduction of energy and inefficient energy usage was addressed. To compare energy usage, a variable known as Energy per Capita was computed which is the division of the Total Annual Power Sales (in kWh) by the Municipal Population. Power generation was compared across different regions using the reported energy generation capacity in each region. A DBScan Machine Learning Algorithm 


<a href = "IBMHackathon.html">Hackathon</a>
For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/damianohienmhen/IBM/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
