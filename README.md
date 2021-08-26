

# Web Design Homework - Web Visualization Dashboard (Latitude)

 This is the link for the web page :   https://shuchik38.github.io/Web_Design_Challenge/
 
 ---------------------------------------------------------

For this homework we'll be creating a visualization dashboard website using visualizations we've created in a past assignment. Specifically, we'll be plotting 'WeatherPy' 

In building this dashboard, we'll create individual pages for each plot and a means by which we can navigate between them. These pages will contain the visualizations and their corresponding explanations. We'll also have a landing page, a page where we can see a comparison of all of the plots, and another page where we can view the data used to build them.

## Latitude - Latitude Analysis Dashboard

![main page]![Main](https://user-images.githubusercontent.com/81253160/131045590-7dfef9bc-264e-4e76-b07e-585e546c1005.png)





For this homework we'll be creating a visualization dashboard website using visualizations we've created in a past assignment. Specifically, we'll be plotting [weather data](Resources/cities.csv).

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



### Screenshots

This section contains screenshots of each page that are built.

<img width="1317" alt="max temp and latitude" src="https://user-images.githubusercontent.com/81253160/130253793-705a946a-4c39-49bf-b4b3-fce4c84cd2e1.png">
<img width="1317" alt="cloudiness" src="https://user-images.githubusercontent.com/81253160/130253866-a4562198-94d5-4336-94f9-8f44f8d4f8e4.png">
<img width="1317" alt="humidity" src="https://user-images.githubusercontent.com/81253160/130253887-2d613a74-e67b-4beb-9b3d-ac4ef2ae4cec.png">
<img width="1317" alt="wind speed" src="https://user-images.githubusercontent.com/81253160/130253897-2e7e2b1a-de59-4702-a69b-3803c99acdfe.png">
<img width="1317" alt="comparision" src="https://user-images.githubusercontent.com/81253160/130253909-dff5868e-8e0b-4091-9b43-ab8676ec9b33.png">
<img width="1317" alt="data" src="https://user-images.githubusercontent.com/81253160/130253919-967b547e-2a72-4a05-a72e-2613ee883d68.png">
