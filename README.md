# Web Design Homework - Web Visualization Dashboard (Latitude)

## Background

Data is more powerful when we share it with others! Let's take what we've learned about HTML and CSS to create a dashboard showing off the analysis we've done.

![image](https://user-images.githubusercontent.com/79428102/132827415-9abe497f-ccdf-4c84-a7c6-aed105fe416b.png)


## Latitude - Latitude Analysis Dashboard with Attitude

For this challenge we'll be creating a visualization dashboard website using visualizations we've created in a past assignment. Specifically, we'll be plotting [weather data](Resources/cities.csv).

In building this dashboard, we'll create individual pages for each plot and a means by which we can navigate between them. These pages will contain the visualizations and their corresponding explanations. We'll also have a landing page, a page where we can see a comparison of all of the plots, and another page where we can view the data used to build them.

### Website Requirements

For reference, see the ["Screenshots" section](#screenshots) below.

The website must consist of 7 pages total, including:

* A [landing page](#landing-page) containing:
  * An explanation of the project.
  * Links to each visualizations page. There should be a sidebar containing preview images of each plot, and clicking an image should take the user to that visualization.
* Four [visualization pages](#visualization-pages), each with:
  * A descriptive title and heading tag.
  * The plot/visualization itself for the selected comparison.
  * A paragraph describing the plot and its significance.
* A ["Comparisons" page](#comparisons-page) that:
  * Contains all of the visualizations on the same page so we can easily visually compare them.
  * Uses a Bootstrap grid for the visualizations.
    * The grid must be two visualizations across on screens medium and larger, and 1 across on extra-small and small screens.
* A ["Data" page](#data-page) that:
  * Displays a responsive table containing the data used in the visualizations.
    * The table must be a bootstrap table component. [Hint](https://getbootstrap.com/docs/4.3/content/tables/#responsive-tables)
    * The data must come from exporting the `.csv` file as HTML, or converting it to HTML. Try using a tool you already know, pandas. Pandas has a nifty method approprately called `to_html` that allows you to generate a HTML table from a pandas dataframe. See the documentation [here](https://pandas.pydata.org/pandas-docs/version/0.17.0/generated/pandas.DataFrame.to_html.html)

The website must, at the top of every page, have a navigation menu that:

* Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
* Contains a dropdown menu on the right of the navbar named "Plots" that provides a link to each individual visualization page.
* Provides two more text links on the right: "Comparisons," which links to the comparisons page, and "Data," which links to the data page.
* Is responsive (using media queries). The nav must have similar behavior as the screenshots ["Navigation Menu" section](#navigation-menu) (notice the background color change).

Finally, the website must be deployed to GitHub pages.

When finished, submit to BootcampSpot the links to 1) the deployed app and 2) the GitHub repository.

Ensure your repository has regular commits (i.e. 20+ commits) and a thorough README.md file

### Considerations

* You may use the [weather data](Resources/cities.csv) or choose another dataset. Alternatively, you may use the included [cities dataset](Resources/cities.csv) and pull the images from the [assets folder](Resources/assets).
* You must use Bootstrap. This includes using the Bootstrap `navbar` component for the header on every page, the bootstrap table component for the data page, and the Bootstrap grid for responsiveness on the comparison page.
* You must deploy your website to GitHub pages, with the website working on a live, publicly accessible URL as a result.
* Be sure to use a CSS media query for the navigation menu.
* Be sure your website works at all window widths/sizes.
* Feel free to take some liberty in the visual aspects, but keep the core functionality the same.

### Bonuses

* Use a different dataset! The requirements above still hold, but make it your own.
* Use a Bootstrap theme to customize your website. You may use a tool like [Bootswatch](https://bootswatch.com/). Make it look snazzy, give it some attitude. If using this, be sure you also meet all of the requirements listed above.
* Add extra visualizations! The more comparisons the better, right?
* Use meaningful glyphicons next to links in the header.
* Have visualization navigation on every visualizations page with an active state. See the screenshots below.

### Screenshots

This section contains screenshots of each page that must be built, at varying screen widths. These are a guide; you can meet the requirements without having the pages look exactly like the below images.

#### <a id="landing-page"></a>Landing page

Large screen:

![image](https://user-images.githubusercontent.com/79428102/132827611-591ed417-8bb9-4204-9db4-96058839c71b.png)

Small screen:

![image](https://user-images.githubusercontent.com/79428102/132827684-8d2d5665-24a9-422d-b6ba-2714b039e305.png)


#### <a id="comparisons-page"></a>Comparisons page

Large screen:

![image](https://user-images.githubusercontent.com/79428102/132827792-133b033a-812c-47ce-9748-3175f13bdcb1.png)

Small screen:

![image](https://user-images.githubusercontent.com/79428102/132827886-9830cffd-1aec-4827-b3a6-b7c0ab873ae3.png)

#### <a id="data-page"></a>Data page

Large screen:

![image](https://user-images.githubusercontent.com/79428102/132827972-bb1a47b7-c8a6-40ba-8416-6eff45c7da76.png)


Small screen:

![image](https://user-images.githubusercontent.com/79428102/132828042-80893884-950d-4a0a-8855-f386ac8446ee.png)

#### <a id="visualization-pages"></a>Visualization pages

You'll build four of these, one for each visualization. Here's an example of one:

Large screen:

![image](https://user-images.githubusercontent.com/79428102/132828125-5896797b-ae94-4744-b925-6473b766242b.png)

Small screen:

![image](https://user-images.githubusercontent.com/79428102/132828158-859dc5a2-5db1-4341-8bb0-1225c1d10996.png)

#### <a id="navigation-menu"></a>Navigation menu

Large screen:
![image](https://user-images.githubusercontent.com/79428102/132828219-e3f447f6-ad34-469d-b529-5003d77698ec.png)

Small screen:
![image](https://user-images.githubusercontent.com/79428102/132828258-aa947535-fe64-4c30-8a53-3fa123102014.png)

### Copyright

© 2021 Trilogy Education Services, LLC, a 2U, Inc. brand. Confidential and Proprietary. All Rights Reserved.
