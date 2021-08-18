# Web Design Homework - Web Visualization Dashboard 
Data is more powerful when we share it with others! Let's see what I've learned about HTML and CSS to create a dashboard showing off the analysis I've done.

## Landing page

Bootstrap css was referred and style css file has been created to be used for each web page. 
Here is the first page view as below: 

![Images/landingResize.png](webpages-images/index.png)


* A landing page containing:
  * An explanation of the project.
  * Links to each visualizations page. There is a sidebar containing preview images of each plot, and clicking an image should take the user to that visualization.
* Four visualization pages, each with:
  * A descriptive title and heading tag.
  * The plot/visualization itself for the selected comparison.
  * A paragraph describing the plot and its significance.
* A comparison page that:
  * Contains all of the visualizations on the same page so we can easily visually compare them.
  * Uses a Bootstrap grid for the visualizations.
* A data page that:
  * Displays a responsive table containing the data used in the visualizations.
    * The table contains a bootstrap table component (table-responsive and table-striped). 
    * The data converted from the `.csv` file as HTML by using jupyter notebook. 
  

The website has all pages at the top of every page, have a navigation menu that:

* Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
* Contains a dropdown menu on the right of the navbar named "Plots" that provides a link to each individual visualization page.
* Provides two more text links on the right: "Comparison," which links to the comparison page, and "Data," which links to the data page.
* Is responsive (using media queries). The nav has similar behavior such as changing color or moving the nav to the different view when the pages get smaller. 
Finally, the website must be deployed to GitHub pages.

When finished, submit to BootcampSpot the links to 1) the deployed app and 2) the GitHub repository.

Ensure your repository has regular commits (i.e. 20+ commits) and a thorough README.md file


### Screenshots

This section contains screenshots of each page.

#### <a id="index-page"></a>Landing page

Large screen:

![Landing page large screen](webpages-images/index.png)

Small screen:

![Landing page small screen](webpages-images/smalllanding.png)

#### <a id="max-temperature"></a>Max Temperature page


![max temprature screen](webpages-images/maxtemperature.png)

#### <a id="humidity"></a>Humidity page


![humidity](webpages-images/humidity.png)

#### <a id="cloudiness"></a>Cloudiness page


![cloudiness](webpages-images/cloudiness.png)

#### <a id="windspeed"></a>Wind Speed page


![windspeed](webpages-images/windspeed.png)

#### <a id="comparisons-page"></a>Comparison page


![comparison page screen](webpages-images/comparison.png)


#### <a id="data-page"></a>Data page


![data page screen](webpages-images/data.png)

#### <a id="navigation-menu"></a>Navigation menu

Large screen:

![nav menu large screen](webpages-images/navigation.png)

Small screen:

![small screen](webpages-images/navigationmedia.png)

## References

OpenWeatherMap.org. (2012). Сurrent weather and forecast. Retrieved from [https://openweathermap.org/](https://openweathermap.org/)