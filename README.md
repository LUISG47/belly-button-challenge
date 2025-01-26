# MODULE 14 CHALLENGUE 

In this assignment, you will build an interactive dashboard to explore the Belly Button Biodiversity dataset which catalogs the microbes that colonize human navels.

The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.

Url of the app within github pages: https://luisg47.github.io/belly-button-challenge/


## Instructions

Complete the following steps:

1. Use the D3 library to read in samples.json from the URL https://static.bc-edx.com/data/dl-1-2/m14/lms/starter/samples.json. (This file is also available on the root folder so you can see the structure or call it locally)
2. Create a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.
+ Use sample_values as the values for the bar chart.
+ Use otu_ids as the labels for the bar chart.
+ Use otu_labels as the hovertext for the chart.

![Screenshot 2025-01-24 at 9 57 27 p m](https://github.com/user-attachments/assets/874f2efc-315e-4a5e-a13c-a82fe8ff95f8)

3. Create a bubble chart that displays each sample.

+ Use otu_ids for the x values.
+ Use sample_values for the y values.
+ Use sample_values for the marker size.
+ Use otu_ids for the marker colors.
+ Use otu_labels for the text values.

![Screenshot 2025-01-24 at 9 57 32 p m](https://github.com/user-attachments/assets/79b9f073-aaa0-40bf-8a5e-560b13bc6a2e)

4. Display the sample's metadata, i.e., an individual's demographic information.

+ Loop through each key-value pair from the metadata JSON object and create a text string.
+ Append an html tag with that text to the #sample-metadata panel.

![Screenshot 2025-01-24 at 9 57 37 p m](https://github.com/user-attachments/assets/4b75c750-c32d-49c3-8b93-938201752ced)

5. Update all the plots when a new sample is selected. Additionally, you are welcome to create any layout that you would like for your dashboard. An example dashboard is shown as follows:

![Screenshot 2025-01-24 at 9 57 21 p m](https://github.com/user-attachments/assets/eb09f5cb-dbde-433f-b497-6c5bb1eddce0)





6. Deploy your app to a free static page hosting service, such as GitHub Pages: https://luisg47.github.io/belly-button-challenge/

