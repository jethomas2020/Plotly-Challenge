# Plotly-Challenge
plot.ly Challenge


Plot.ly Homework - Belly Button Biodiversity

Bacteria by filterforge.com

In this assignment, you will build an interactive dashboard to explore the Belly Button Biodiversity dataset, which catalogs the microbes that colonize human navels.

The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.

The dataset is included as samples.json
Step 1: Plotly

    Populate a dropdown menu with all of the Sample ID's. When an option is selected, this will update all of the charts.

    N.B. If you look in your index.html, the event function optionChanged() is already included. This function takes the value of each dropdown option. You need to define this function in your javascript.

    Create a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.

        Use sample_values as the values for the bar chart.
            N.B. For each sample, the OTU's are listed in descending order.

        Use otu_ids as the labels for the bar chart.
            HINT: Labels should be strings, not numbers.

        Use otu_labels as the hovertext for the chart.

bar Chart

    Create a bubble chart that displays each sample.

        Use otu_ids for the x values.

        Use sample_values for the y values.

        Use sample_values for the marker size.

        Use otu_ids for the marker colors.

        Use otu_labels for the text values.

    Bubble Chart

    Display sample metadata, i.e., an individual's demographic information.
        Display each key-value pair from the metadata JSON object somewhere on the page.

hw

We have provided an index.html with an example layout, but feel free to create your own.

    N.B. The sample index.html was created using an older version of Bootstrap.

hw
Advanced Challenge Assignment (Optional)


Super Advanced Challenge Assignment (Optional)

Create your own meaningful chart using plotly.
Deployment

    Deploy your page to GitHub pages. Include both the deployment and repository links in your Bootcampspot submission.

    Ensure your repository has regular commits (i.e. 20+ commits) and a thorough README.md file

Hints

    Use console.log inside of your JavaScript code to see what your data looks like at each step.

    Refer to the Plotly.js documentation when building the plots.

About the Data

Hulcr, J. et al.(2012) A Jungle in There: Bacteria in Belly Buttons are Highly Diverse, but Predictable. Retrieved from: http://robdunnlab.com/projects/belly-button-biodiversity/results-and-data/