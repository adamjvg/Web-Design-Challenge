# Web-Design-Challenge
Skip to content
GitLab
Menu
Search GitLab
Help
Adam Van Geleuken
W
WAUS-VIRT-DATA-PT-12-2021-U-C
Project information
Repository
Issues0
Merge requests0
CI/CD
Security & Compliance
Deployments
Monitor
Infrastructure
Packages & Registries
Analytics
Wiki
Snippets
The University of Western Australia
WAUS-VIRT-DATA-PT-12-2021-U-C
Repository
master
waus-virt-data-pt-12-2021-u-c
11-Web
3-Homework
README.md
nictanc's avatar
Week 11 Web
nictanc authored 1 week ago
ae7f24ab
  README.md  6.39 KB
Web Design Homework - Web Visualisation Dashboard (Latitude)
Background
Data is more powerful when we share it with others! Let's take what we've learned about HTML and CSS to create a dashboard showing off the analysis we've done.

Images/landingResize.png

Before You Begin
Create a new repository for this project called Web-Design-Challenge. Do not add this homework to an existing repository.

Clone the new repository to your computer.

Inside your local git repository, create a directory for the web challenge. Use a folder name to correspond to the challenge: WebVisualisations.

Add your html files to this folder as well as your assets, Resources and visualisations folders.

Push the above changes to GitHub or GitLab.

Deploy to GitHub pages.

Latitude - Latitude Analysis Dashboard with Attitude
For this homework we'll be creating a visualisation dashboard website using visualisations we've created in a past assignment. Specifically, we'll be plotting weather data.

In building this dashboard, we'll create individual pages for each plot and a means by which we can navigate between them. These pages will contain the visualisations and their corresponding explanations. We'll also have a landing page, a page where we can see a comparison of all of the plots, and another page where we can view the data used to build them.

Website Requirements
For reference, see the "Screenshots" section below.

The website must consist of 7 pages total, including:

A landing page containing:
An explanation of the project.
Links to each visualisations page. There should be a sidebar containing preview images of each plot, and clicking an image should take the user to that visualisation.
Four visualisation pages, each with:
A descriptive title and heading tag.
The plot/visualisation itself for the selected comparison.
A paragraph describing the plot and its significance.
A "Comparisons" page that:
Contains all of the visualisations on the same page so we can easily visually compare them.
Uses a Bootstrap grid for the visualisations.
The grid must be two visualisations across on screens medium and larger, and 1 across on extra-small and small screens.
A "Data" page that:
Displays a responsive table containing the data used in the visualisations.
The table must be a bootstrap table component. Hint
The data must come from exporting the .csv file as HTML, or converting it to HTML. Try using a tool you already know, pandas. Pandas has a nifty method appropriately called to_html that allows you to generate a HTML table from a pandas dataframe. See the documentation here
The website must, at the top of every page, have a navigation menu that:

Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
Contains a dropdown menu on the right of the navbar named "Plots" that provides a link to each individual visualisation page.
Provides two more text links on the right: "Comparisons," which links to the comparisons page, and "Data," which links to the data page.
Is responsive (using media queries). The nav must have similar behaviour as the screenshots "Navigation Menu" section (notice the background color change).
Finally, the website must be deployed to GitHub pages.

When finished, submit to BootcampSpot the links to 1) the deployed app and 2) the GitHub repository.

Considerations
You may use the weather data or choose another dataset. Alternatively, you may use the included cities dataset and pull the images from the assets folder.
You must use Bootstrap. This includes using the Bootstrap navbar component for the header on every page, the bootstrap table component for the data page, and the Bootstrap grid for responsiveness on the comparison page.
You must deploy your website to GitHub pages, with the website working on a live, publicly accessible URL as a result.
Be sure to use a CSS media query for the navigation menu.
Be sure your website works at all window widths/sizes.
Feel free to take some liberty in the visual aspects, but keep the core functionality the same.
Bonuses
Use a different dataset! The requirements above still hold, but make it your own.
Use a Bootstrap theme to customise your website. You may use a tool like Bootswatch. Make it look snazzy, give it some attitude. If using this, be sure you also meet all of the requirements listed above.
Add extra visualisations! The more comparisons the better, right?
Use meaningful glyphicons next to links in the header.
Have visualisation navigation on every visualisations page with an active state. See the screenshots below.
Screenshots
This section contains screenshots of each page that must be built, at varying screen widths. These are a guide; you can meet the requirements without having the pages look exactly like the below images.

Landing page
Large screen:

Landing page large screen

Small screen:

Landing page small screen ￼

Comparisons page
Large screen:

comparison page large screen

Small screen:

comparison page small screen

Data page
Large screen:

data page large screen

Small screen:

data page small screen

Visualisation pages
You'll build four of these, one for each visualisation. Here's an example of one:

Large screen:

visualize page large screen

Small screen:

visualize page small screen

Navigation menu
Large screen: nav menu large screen

Small screen: nav menu small screen

Copyright
© 2021 Trilogy Education Services, LLC, a 2U, Inc. brand. Confidential and Proprietary. All Rights Reserved.