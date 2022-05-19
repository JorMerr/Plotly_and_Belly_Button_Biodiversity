## Plotly and Belly Button Biodiversity

### Overview of Project
The purpose of this project is to provide an interactive dashboard for study volunteers to review the Top 10 bacterial species found in their belly button. This dashboard will allow volunteers to quickly view whether their natural bacteria may be a candidate for Improbably Beef to manufacture synthetic beef.
#### Steps of the Project
The `plots.js` file was updated to dynamically display a dashboard containing the following features:

##### Bar Chart
A bar chart of the Top 10 bacteria species found in a subject's belly button which would dynamically update when the Subject ID was changed from the dropdown menu.

![Bar Chart](https://github.com/JorMerr/Plotly_and_Belly_Button_Biodiversity/blob/main/static/img/BarChart.PNG)

##### Bubble Chart
A bubble chart of all the bacteria species found in a subject's belly button, and the volume at which it was found which would dynamically update when the Subject ID was changed from the dropdown menu.

![Bubble Chart](https://github.com/JorMerr/Plotly_and_Belly_Button_Biodiversity/blob/main/static/img/BubbleChart.PNG)

##### Gauge Chart
A guage chart displaying the frequency with which the subject reposted to wash their belly button each week which would dynamically update when the Subject ID was changed from the dropdown menu.

![Gauge Chart](https://github.com/JorMerr/Plotly_and_Belly_Button_Biodiversity/blob/main/static/img/GaugeChart.PNG)


#### Additional Stylings
The following additional customizations were added to the original Bootstrap template provided:

- A background image was added to the jumbotron
    - image sourced from "https://wallpaperaccess.com/bacteria#google_vignette"
- The text colour of the jumbotron was changed to compliment the background image
- The background colour was updated for the body of the site
- Dynamic resizing and breakpoints of some elements were added to allow for mobile responsiveness
- Background and text colours were changed in the Dropdown Menu container and the Demographic Info container to complement the background colour of the page
- Additional information was added below each graph to describe what is visualized
- Additional line breaks were added between the row containing the Bar and Gauge Charts, and the Bubble Chart so that the spacing of elements was more visually pleasing.



*This project created by Jordan Merritt as part of Carleton University's Business Data Analysis and Visualization Boot Camp.*