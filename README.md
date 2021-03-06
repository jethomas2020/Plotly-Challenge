# Plotly-Challenge


# Plot.ly Project - Belly Button Biodiversity

# Background

In this assignment, we will build an interactive dashboard to explore the Belly Button Biodiversity dataset, which catalogs the microbes that colonize human navels.

# Data 

The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.

The dataset is included as samples.json


# Plot.ly Project Steps

    1. Populate a dropdown menu with all of the Sample ID's. When an option is selected, this will 
        update all of the charts.

    Within the index.html, the event function optionChanged() is already included.
    This function takes the value of each dropdown option. We defined this function in the javascript.

    2. Created a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in 
        that individual.

        Used sample_values as the values for the bar chart.
            For each sample, the OTU's are listed in descending order.

        Used otu_ids as the labels for the bar chart.
            Labels should be strings, not numbers.

        Used otu_labels as the hovertext for the chart.


    3. Created a bubble chart that displays each sample.

        Used otu_ids for the x values.

        Used sample_values for the y values.

        Used sample_values for the marker size.

        Used otu_ids for the marker colors.

        Used otu_labels for the text values.



    4. Displayed sample metadata, i.e., an individual's demographic information.
        Display each key-value pair from the metadata JSON object somewhere on the page.

----------------------------
index.html

We have provided an index.html with an example layout. Used Bootstrap.


----------------------------------------------------
**Deployment**

    Deploy your page to GitHub pages: https://jethomas2020.github.io/Plotly-Challenge/

---------------------------------------------   
**Hints**

    Use console.log inside of your JavaScript code to see what your data looks like at each step.

    Refer to the Plotly.js documentation when building the plots.

-----------------------------------------------
**About the Data**

Hulcr, J. et al.(2012) A Jungle in There: Bacteria in Belly Buttons are Highly Diverse, but Predictable. Retrieved from: http://robdunnlab.com/projects/belly-button-biodiversity/results-and-data/

-------------------------------
**Site published at:**   https://jethomas2020.github.io/Plotly-Challenge/

