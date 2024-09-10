# majorstudio1

Islamic Art(ifacts) by Sultanate Period

My main goal was to go deeper into the bucket that is “Islamic Art”, and categorize it on a more micro level. I wanted to ask – how can an understanding of Islamic Art be made more complex by understanding it through a non-western timeline, aka, through Sultanates instead of “Ages”. This helps visualize when in Islamic history were their booms of artistic and creative production.

https://api.si.edu/openaccess/api/v1.0/search?q=online_visual_material:true+AND+type:edanmdm+AND+islamic+AND+art+AND+period&api_key=[your key]
The dataset includes as much as is accessible (through these specific keywords) about the “Period” under “label”. I am trying to figure out more ways of finding this data since it shows there to be 300+ islamic artifacts that are definitely categorized by dates, from which I can figure out the period if not explicitly mentioned.

I chose to use a Sankey Diagram since I wanted a “fluid” connecting tether showing HOW much islamic art is at once from a specific period and how much it accounts for the total art categories throughout history. I wanted there to be a striated and nested way to see at a glance the period, how much % of the art made in a period was in specific categories, and how much that ends up accounting for the total % in each category for the entire provided timeline of the islamic world.

<img width="464" alt="sankey" src="https://github.com/user-attachments/assets/20335b91-98b3-4ce4-84e7-5001ba566986">

“Fragments: A Comparative World-Wide Analysis”


The questions I wanted to explore with this data set are – 
What do fragments of artifacts that were not recovered tell us about the era they are dated to?
Is there any trend of fragment material being very frequently used and slowly discontinued over time of that material (since perhaps they were more susceptible to fragmentation, and could not sustain as a full object or artifact)?
How does the region / continent affect the materials used, and also affect the type of fragment found?
How can the type of fragment found give us insight about everyday culture of the region? 
How does this everyday culture change over each era for each region? 
How, on a macro level, has use of material changed over the world timeline? Do phenomena like trade and colonization affect materials being transported and adopted for use in other regions?


Data set: “https://www.si.edu/search/collection-images?edan_q=fragments&edan_fq%5B0%5D=place%3A%22Africa%22%20OR%20place%3A%22Asia-Temperate%22%20OR%20place%3A%22Asia-Tropical%22%20OR%20place%3A%22Europe%22&edan_fq%5B1%5D=media_usage%3A%22CC0%22”
(I tried searching on Edan, but it was giving me issues every time I tried to add multiple keywords, or everytime i added the “AND/+AND” command in the overall API URL, saying “no results found”.)

The data set is any result that has “Fragments” in its title or description. The properties available in this data set are “Place (from which i chose the continents)”, “Topic” (material of fragment), “Resource Type” (types of fragments), and “Date” (used to calculate ‘era’). There’s a total of 11,000~ data points that are images of the fragments.


The visualization method used is a Doughnut Chart. This is because “fragments” refer to parts of a whole, so the idea of each doughnut being filled with percentage fragments felt correct, as the form is matching the content being documented.

<img width="392" alt="native american" src="https://github.com/user-attachments/assets/575e59b4-8d45-4d97-afa7-d34d8da262a4">

Archiving Quotidien American Indian Artifacts

With this visualization, I wanted to see a comparison between artifacts that exist from the Indians of North America vs those of South America and whether the growth of both collections is incremental / linear or not. I wanted to see what types of everyday artifacts are found and their frequency by year. Also, since the term “Native American” only invokes the hegemonic North American natives, I wanted to see if the museum collection of artifacts from Indians of South America is as holistic and given as much importance for collections in all categories compared to north american indians.

https://www.si.edu/search/collection-images?edan_q=Indians%2Bof%2BNorth%2BAmerica&Indians%2Bof%2BSouth%2BAmerica since again, I wasn’t able to find this in API form, I used the SI OA site to find the topics / keywords for this sata set. It includes Indians from South America and North America as one of the 2 variables (Region), and Type of Quotidien Object (Artifact) as the other.

I wanted to use a Spider/Radar chart specifically so it can give a blob like expanding/contracting sensation over time to be able to form a visual cue of increase and decrease of both the North American Indian and South American Indian artifact collection, while also being able to laterally compare both the variables to each other to derive insights of why there is (or isn't) disparity between each as time progresses. 


<img width="498" alt="fragments" src="https://github.com/user-attachments/assets/8c07393a-9aa1-4abc-8a61-1ffbfb37d807">
