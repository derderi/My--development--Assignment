# My--development--Assignment
shiny slider
What is Shiny?

Shiny is a web application framework for R.
Shiny allows you to create a graphical interface so that users can interact with your visualizations, models, and algorithms without needed to know R themselves.
Using Shiny, the time to create simple, yet powerful, web-based interactive data products in R is minimized.
Shiny is made by the fine folks at R Studio.
Some Mild Prerequisites

Shiny doesn't really require it, but as with all web programming, a little knowledge of HTML, CSS and Javascript is very helpful.

HTML gives a web page structure and sectioning as well as markup instructions
CSS gives the style
Javscript for interactivity
Shiny uses Bootstrap (no relation to the statistics bootstrap) style, which (to me) seems to look nice and renders well on mobile platforms.

Availible Tutorials

If you're interested in learning more about HTML, CSS, and Javascript we recommend any one of the following resources:

Mozilla Developer Network Tutorials
HTML & CSS from Khan Academy
Tutorials from Free Code Camp
Getting Started

Make sure you have the latest release of R installed
If on Windows, make sure that you have Rtools installed
install.packages("shiny")
library(shiny)
Great tutorial at http://shiny.rstudio.com/tutorial/
Basically, this lecture is walking through that tutorial offering some of our insights
A Shiny project

A shiny project is a directory containing at least two files:

ui.R (for user interface) controls how your app looks.
server.R that controls what your app does.
