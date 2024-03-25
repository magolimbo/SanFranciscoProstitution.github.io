---
layout: default
---

The [San Francisco Crime dataset](https://data.sfgov.org/Public-Safety/Police-Department-Incident-Reports-Historical-2003/tmnf-yvry/about_data) is a free dataset that provides valuable information about over 2 million crimes in San Francisco **from 2003 to May 2018**. Each entry in the dataset is a crime recorded by the police, indicating the category, time, and location of the crime, as well as other useful information.

For the purpose of the assignment we decided to focus on **prostitution**, to gain insights about its evolution over time and its distribution over San Francisco. From the dataset, **16.501 cases** have been recorded under the category of prostitution over the course of 15 years.

# Across the years: An overview over time

<!-- Robert Selna, Chronicle Staff Writer, wrote this in an article from 2009 on [sfgate.com](https://www.sfgate.com/crime/article/S-F-s-ambiguous-attitude-toward-brothels-3255663.php) -->
Robert Selna, Chronicle Staff Writer, wrote this in an article from 2009 on [sfgate.com](https://www.sfgate.com/crime/article/S-F-s-ambiguous-attitude-toward-brothels-3255663.php)
>Since even before the Gold Rush, the city has been ambivalent about the sex industry. In 1849, nearly two-thirds of the 300 women in San Francisco were prostitutes, according to some estimates. And although prostitution was illegal in 1911, the city's health board ran a medical clinic for sex workers.


![prostitution occurences](images/prostitution_occurences1.png)

Today, the situation has significantly improved. As evidenced by the histogram, since 2008 the trend has dropped dramatically, reaching **523 cases in 2017**, compared to the **1937 cases in 2003**, that is more than 5 reports per day. This drastic drop is due to changes in the law, in policing strategy, law enforcement’s increased focus on human trafficking and in the way sex work is viewed by the powers that be.

What stands out is the temporary decrease in occurrences between 2004 and 2006, possibly linked to the major operation in 2005 involving 400 federal and state law enforcement officials who **dismantled 50 brothels** and other businesses in San Francisco and the Bay Area involved in the **trafficking of South Korean women forced into prostitution.** 
<!-- (read the article from the New York Times [here](https://www.nytimes.com/2005/07/02/us/agents-said-to-dismantle-a-korean-sex-ring.html)). -->

It is also important to note that the number of reports classified as prostitution in this dataset likely includes cases of **loitering**, considered a crime by the California Penal Code until 2023 if associated with the intent to commit prostitution. Therefore, the number of actual prostitution cases is likely lower than what appears.

# Mapping Prostitution: Exploring Hotspots in San Francisco

**Table: Incidence of Prostitution by District**

| District    | Value |
|:-------------|:-------|
| BAYVIEW     | 136   |
| CENTRAL     | 1854  |
| INGLESIDE   | 80    |
| **MISSION**     | **7307**  |
| NORTHERN    | 3945  |
| PARK        | 18    |
| RICHMOND    | 64    |
| SOUTHERN    | 690   |
| TARAVAL     | 413   |
| TENDERLOIN  | 1994  |

It's not a surprise that almost all the prostitution incidents have been recorded in the **Mission District**, that counts **7307 occurences**, followed by Northern with 3945.
The Mission district (see map below), and particularly **Capp Street**, is notoriously famous for its high incidence of prostitution, which has even led authorities to build concrete barriers to reduce the influx of clients from outside. The barricades have significantly improved the safety of Capp. St. over the past months bringing peace and quiet. A solution that neighbors in the area deem necessary for the neighborhood's sanity and safety.
However this solution only partially solved the problem, as the sex workers were simply moved a few blocks away.

This clearly suggests that the underlying issue is not preventing clients from reaching sex workers, but rather increasing efforts to dismantle the criminal organizations that control hundreds of women, or even legalizing and regulating prostitution to remove these human lives from the streets.


<embed 
       type="text/html" 
       src="prostitution_map.html"
       width="1100"
       height="600"
       >
</embed>




# Mapping Prostitution: An interactive visualisation over time

As seen in this interactive Bokeh plot, the number of crimes related to prostitution has significantly decreased over the years. It is interesting to note that in 2009, the Mission district experienced the highest peak of activity, while all the other districts recorded a significant decline, especially in the northern district. From the plot, it seems that all the criminal activity of that year concentrated in the Mission district. However, in 2015, the lowest number of prostitution crimes was recorded and the Southern district took the lead as the district with the highest prostitution activity. This may imply that, as previously mentioned, various policies against brothels, etc., have had an effect over the years, as the decrease has been progressive for all districts, especially those with high criminal activity. It is important to highlight that districts like Richmond and Bayview have consistently had a very low number of incidents.

This downward trend suggests a positive impact of enforcement measures and possibly social interventions aimed at addressing the underlying issues contributing to prostitution-related crimes. Additionally, it could indicate changes in societal attitudes or economic factors influencing the demand for such activities. The data underscores the importance of ongoing efforts to combat human trafficking and exploitation associated with the sex trade.

An alternative and really interesting visualization of prostitution activity in San Francisco in 2009 is the render below by [Dough McCune](https://dougmccune.com/blog/tag/datasf/), where criminal activity is mapped as elevation relative to sea level. As already confirmed by the previous interactive graph, the Mission district clearly outperforms all others by a significant margin.

![prostitution heightmap](images/prostitution11.png)


<embed 
       type="text/html" 
       src="prostitution_crimes_plot.html"
       width="1100"
       height="600"
       />

Examining the fluctuations in crime rates across different districts can provide valuable insights into the effectiveness of localized interventions and enforcement strategies. By analyzing these trends, policymakers and law enforcement agencies can better target resources and tailor interventions to address specific challenges faced by each community.

In conclusion, while there has been a notable reduction in prostitution-related crimes over the years, continued vigilance and targeted interventions are necessary to sustain this positive trend and address any remaining issues effectively. Collaboration between law enforcement, social services, and community stakeholders remains crucial in tackling the complex issues surrounding prostitution and ensuring the safety and well-being of vulnerable populations..
