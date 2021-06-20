# Web-Design-Challenge 

Student Assignment displaying results from prior analysis done in python-api-challenge through Github pages using HTML, CSS, and Bootstrap.  

### Latitude - Latitude Analysis Dashboard with Attitude ###

For this homework we'll be creating a visualization dashboard website using visualizations we've created in a past assignment. Specifically, we'll be plotting weather data.

In building this dashboard, we'll create individual pages for each plot and a means by which we can navigate between them. These pages will contain the visualizations and their corresponding explanations. We'll also have a landing page, a page where we can see a comparison of all of the plots, and another page where we can view the data used to build them. 

### The website must consist of 7 pages total, including: ###
### A landing page containing: ###
  1. An explanation of the project.
  2. Links to each visualizations page. There should be a sidebar containing preview images of each plot, and clicking an image should take the user to that visualization.

### Four visualization pages, each with: ###
  1. A descriptive title and heading tag.
  2. The plot/visualization itself for the selected comparison.
  3. A paragraph describing the plot and its significance.

### A "Comparisons" page that: ###
  1. Contains all of the visualizations on the same page so we can easily visually compare them.
  2. Uses a Bootstrap grid for the visualizations.
      - The grid must be two visualizations across on screens medium and larger, and 1 across on extra-small and small screens.

### A "Data" page that: ###
  1. Displays a responsive table containing the data used in the visualizations.
  2. The table must be a bootstrap table component. Hint: The data must come from exporting the .csv file as HTML, or converting it to HTML. Try using a tool      you already know, pandas. Pandas has a nifty method appropriately called to_html that allows you to generate a HTML table from a pandas dataframe. See the      documentation here

### The website must, at the top of every page, have a navigation menu that: ###
  1. Has the name of the site on the left of the nav which afllows users to return to the landing page from any page.
  2. Contains a dropdown menu on the right of the navbar named "Plots" that provides a link to each individual visualization page.
  3. Provides two more text links on the right: "Comparisons," which links to the comparisons page, and "Data," which links to the data page.
  4. Is responsive (using media queries). The nav must have similar behavior as the screenshots "Navigation Menu" section (notice the background color change).
  5. Finally, the website must be deployed to GitHub pages.

https://bennetyousuf.github.io/Web-Design-Challenge/
