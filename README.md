# U.S. Honey Bees: A look into colony fluctuation and stressors of U.S. commercial honey bees in 2015-2020

## Table of Contents
* [Why Bees?](#Why-Bees?)   
* [Data Questions](#Data-Questions)
* [Technologies](#Technologies)
* [The Process](#The-Process)
* [Link to the Site with Data Sources](#Link-to-the-Site-with-Data-Sources)

## Why Bees?
<details>
  <summary>Bees don't just provide us with delicious honey and a beautifully diverse world of flowering plants, they keep us fed too! </summary>   


  While deciding what to dive into for my capstone project, I knew I wanted to pick a topic that I would find interesting to learn about, which would hopefully be interesting to other people, too. I was reading a book about the perplexing nature of a bee's mind and the hardships they face as foragers, which made me curious about the role they play as an important part of the food chain. I wanted to consider how they contribute to our agriculture and food production. 
  
  Over the past few decades, the population of both wild and commercial bees has been in fluctuation or decline. Because bees pollinate many food crops, they have an immense importance to agriculture and food stability for people around the world. While there are many pollinator species such as birds and butterflies, honey bees are the most common and important pollinator to domestic agriculture, and keeping their population numbers up is a critical task. 
  
  By exploring 2015-2020 USDA reports on honey bee colonies and honey production, I show how managed honey bee colony population changes by season, what stressors contribute to colony loss or burden, and make connections to stressor impact on colony success. With better understanding of what impacts honey bees, we can better help their numbers grow! 
  
</details>

## Data Questions
1. How do honey bee populations change over time?
2. Where are commercial colonies kept in the U.S.?
3. What environmental factors contribute to colony stressors, and does this affect bee keeping success for the agricultural honey market?

## Technologies  
* Python
  * [Jupyter Notebooks](https://jupyter.org/)
  * [pandas](https://pandas.pydata.org/)
* [Tableau](https://www.tableau.com/)
* [Google Sites](https://workspace.google.com/products/sites/)

## The Process  
<details>
  <summary>Acquiring the data</summary>

Data on colony numbers, colony stressors, honey production, and crop/bee attraction was gathered from the USDA website on pollinators. Data was downloaded from pdf reports. 
</details>  

<details>
  <summary>Cleaning and organizing the data</summary>

The original plan was to scrape pdfs from each site, but due to the irregularity of format, it made more sense to download the reports, convert the reports from pdf to csv format, then isolate the partial tables and convert them to full tables. Reports were combined and formatted as needed to form dataframes. 

</details>

<details>
  <summary>Visualizations</summary>

After using matplotlib in python to map out my analysis of the gathered data, I moved the data to Tableau for final visualizations. My goals were to clearly show how many USDA crops commercial honey bees pollinate, honey bee population fluctuations, honey production by state, and stressor impacts on colonies. For my final presentation, I embedded my Tableau visualizations onto a google site which you can find below.

</details>

## Link to the Site with Data Sources
Enjoy clicking through the [site](https://sites.google.com/view/us-honey-bees/home) to satiate your own curiosity on U.S. honey bees! 
