# Belly Button Biodiversity

## Overview
Roza is a biological researcher in a prominent micro-biology laboratory. She is interested in bacterial species that have the ability to synthesize proteins that taste like beef.
Her lab has partnered with Improbable Beef, a food startup, to research candidate species.
Roza has a hypothesis that there is a micro-organism that can supply the next best taste and she believes that it can be found from bacteria on the human body. 
Furthermore, her hypothesis is that the ideal bacterial species to make synthetic beef may be found in the belly button. 
To test this hypothesis she has sampled the navals of volunteers from all across the country.
Each volunteer is anonymous and has been assigned an ID number.  
She would like to build a dashboard that both the research participants and fellow researchers can access.
She has a completed panel for demographic information and now needs to visualize the bacterial data for each volunteer. 
Specifically, her volunteers should be able to identify the top 10 bacterial species in their belly buttons. 
That way, if Improbable Beef identifies a species as a candidate to manufacture synthetic beef, Roza's volunteers will be able to identify whether that species is found in their navel.
This dashboard is interactive so that the user can select a test subject's ID number which will then lead the dashboard to display the results associated with that specific ID number.
The results that will be displayed are:
* Demographic Information:
  * Ethnicity
  * Gender
  * Age
  * Location
  * BBType (belly button type)
  * WFreq (wash frequency)
* A bar chart of the top 10 bacteria cultures found
* A bubble chart of bacteria cultures per sample
* A gauge chart of belly button washing frequency

## Results
Starting off I created a demographics panel that displays the volunteers information. 
* <img width="116" alt="demos" src="https://user-images.githubusercontent.com/85372441/132416430-366b963f-04bf-44f8-954b-0673e75bfe15.png">

After which I created __three charts__ using Plotly:
* **Bar Chart**
* <img width="312" alt="bar" src="https://user-images.githubusercontent.com/85372441/132416306-8133cd6d-0faa-4437-b109-64c978de2f32.png">
* **Bubble Chart**
* <img width="790" alt="bubble" src="https://user-images.githubusercontent.com/85372441/132416357-a0dc8c79-e861-41f6-95e9-c761317a3c9d.png">
* **Gauge Chart**
* <img width="333" alt="gauge" src="https://user-images.githubusercontent.com/85372441/132416578-e3c24c03-2f73-4ebc-8d36-9e99e757d8a5.png">

I then customized the dashboard with a few of the following changes:
 * Added an image to the jumbotron
 * Added background color
 * Added information about the project as a paragraph on the page
 * Used a custom for with contrast for the colors.
<img width="932" alt="final" src="https://user-images.githubusercontent.com/85372441/132416642-406de2b3-2fc0-4744-adf9-49d0c38df4eb.png">

