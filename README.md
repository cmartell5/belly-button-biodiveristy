# belly-button-project
An interactive dashboard using HTML, JSON, D3 and JavaScript

# Background
I will be building an interactive dashboard to explore the [Belly Button Biodiversity dataset](http://robdunnlab.com/projects/belly-button-biodiversity/) which catalogs the microbes that colonize human navels.
1. Use the D3 library to read in a JSON file provided for project
2. Create a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.
  - Use sample_values as the values for the bar chart.
  - Use otu_ids as the labels for the bar chart.
  - Use otu_labels as the hovertext for the chart.
  
  ![image](https://user-images.githubusercontent.com/100399092/201748368-bb9878c8-831b-4d3e-90f1-4a30ecfab47f.png)

3. Create a bubble chart that displays each sample.
  - Use otu_ids for the x values.
  - Use sample_values for the y values.
  - Use sample_values for the marker size.
  - Use otu_ids for the marker colors.
  - Use otu_labels for the text values.
  
  ![image](https://user-images.githubusercontent.com/100399092/201748410-b25294a6-aefd-4d0a-8347-446b65bc96ae.png)

4. Display the sample metadata, i.e., an individual's demographic information.
5. Display each key-value pair from the metadata JSON object somewhere on the page.

![image](https://user-images.githubusercontent.com/100399092/201748576-52bc45bf-902c-4c87-8709-3ff591555299.png)

6. Update all the plots when a new sample is selected.
7. Deploy app when completed.

## Deployment page: http://127.0.0.1:5500/belly-button-challenge/index.html 
