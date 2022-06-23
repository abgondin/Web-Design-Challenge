# Output web visualisation dashboard can be tested:
https://abgondin.github.io/Web-Design-Challenge/index.html

# 11 Web Design - Web Visualization Dashboard

## Background

HTML and CSS was used to create a visualization dashboard in a live, publicly accessible URL (Github website). 

For reference, see the ["Screenshots" section](#screenshots) below.

The website consists of 7 pages total, including:

* A [landing page](#landing-page) containing:
  * An explanation of the project.
  * Links to each visualizations page. A sidebar containing preview images of each plot, and clicking an image should take the user to that visualization.

* Four [visualization pages](#visualization-pages), each with:
  * A descriptive title and heading tag.
  * The plot/visualization itself for the selected comparison.
  * A paragraph describing the plot and its significance.
  
* A ["Comparisons" page](#comparisons-page) that:
  * Contains all of the visualizations on the same page so we can easily visually compare them.
  * Uses a Bootstrap grid for the visualizations.
    * The grid adjusts depending on the screen size with two visualizations across on medium and larger screens, and one across on small screens.
  
* A ["Data" page](#data-page) that:
  * Displays a responsive table containing the data used in the visualizations.
    * The table is a bootstrap table component.
    * The data comes from converting a CSV file to HTML.

The website also has a navigation menu at the top of every page that:
* Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
* Contains a dropdown menu on the right of the navbar named "Plots" that provides a link to each individual visualization page.
* Provides two more text links on the right: "Comparisons," which links to the comparisons page, and "Data," which links to the data page.
* Is responsive using media queries.

### Screenshots

This section contains screenshots of each page.

#### <a id="landing-page"></a>Landing page

![Landing page large screen](Images/landingResize.png)

#### <a id="comparisons-page"></a>Comparisons page

![comparison page large screen](Images/comparison-lg.png)

#### <a id="data-page"></a>Data page

![data page large screen](Images/data-lg.png)

#### <a id="visualization-pages"></a>Visualization pages

![visualize page large screen](Images/visualize-lg.png)

#### <a id="navigation-menu"></a>Navigation menu

![nav menu large screen](Images/nav-lg.png)

## Skills

data visualisation | web design | HTML | CSS | bootstrap | responsive tables | navbar | dropdown | GitHub pages
