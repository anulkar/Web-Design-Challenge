# Web Visualization Dashboard (Latitude Analysis)

## https://anulkar.github.io
* Created a visualization dashboard website using visualizations obtained from plotting weather data.
* Created individual pages for each plot and a means by which we can navigate between them. Each page contains the visualizations and their corresponding explanations. The home page (or landing page) provides a summary of the project. Also added a comparison page of all of the plots, and another page where we can view the data used to build them.

## Summary of Web Pages

The website consists of 7 pages total:

* A [landing page](https://anulkar.github.io/) containing:
  * An explanation of the project.
  * Links to each visualizations page.
* Four visualization pages, each with:
  * A descriptive title and heading tag.
  * The plot/visualization itself for the selected comparison.
  * A paragraph describing the plot and its significance.
* A ["Comparisons" page](https://anulkar.github.io/comparisons.html) that:
  * Contains all of the visualizations on the same page so we can easily visually compare them.
  * Uses a bootstrap grid for the visualizations.
* A ["Data" page](https://anulkar.github.io/weather-data.html) that:
  * Displays a responsive table containing the data used in the visualizations.
    * The table is a bootstrap table component.
    * Exported weather data from the [cities.csv](https://github.com/anulkar/Web-Design-Challenge/blob/master/WebVisualizations/Resources/cities.csv) file to an HTML table using [Pandas](https://github.com/anulkar/Web-Design-Challenge/blob/master/WebVisualizations/weather_csv_to_html.ipynb).
