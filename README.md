# Team-10-MIST-4610-Group-Project-2
# Team Name
Group 10 | 21482
# Team Members
1. [Aniketh Venkateswaran](https://github.com/anivenk033)
2. [Fauz Syed](https://github.com/Fauz-Syed?tab=repositories)
3. [Sean Payne](https://github.com/SeanPayne19)
4. [Phillip Doan](https://github.com/phillipdoan10)

# Problem Description
 To analyze Washington State's Electric Vehicle data to derive optimal locations for the placement of charging stations, and ultimately to maximize revenue for charging station providers. This goal can be achieved by creating visualizations with Tableau of EV ownership concentrations in the state, and considering factors like vehicle types and regional vehicle population density.

# Dataset Used
Electric_Vehicle_Population_Data

# Dataset Explanations
Within our dataset titled “Electric Vehicle Population Data” gathered from the public display of databases on Data.Gov, congregates all of the registered electric vehicle information from residents of Washington State. Within these 17 attributes and 181,458 rows, are the instances of the different vehicles which show the Vehicle Identification Number (VIN) as well as  the city and county in which the vehicle coincides. In addition to these attributes, other information about the registration is included such as the make, model, and year of the automobile, as well as the eligibility for clean alternative fuel benefits, the electric range, MSRP and district in which its legislative district remains. Finally one of the most beneficial attributes this table holds is where these registered vehicles are located via latitudinal and longitudinal coordinates which were extremely important to creating the visualizations. 

# Questions to Answer
Analytical Questions to Answer: 

Which counties have the highest population of Electric Vehicles?


What are the top three most popular electric vehicle models within the three counties with the highest population of electric vehicles (King County, Snohomish County, and Pierce County) and how does their distribution vary across these counties?

# Manipulations
The manipulations we made to the data were trivial yet powerful in finding the results we needed. In the first visualization we sorted the longitude into the columns while sorting the latitude into the rows to provide us with the ability on the “show me” feature to display the clusters of electric vehicles. Next, we included marks of the City, County, and Make of the cars. In addition to including the “Make” in the marks section, we also altered the attribute so it would provide us with a distinct count ultimately discarding any unnecessary population clusters that would hinder the visuals of the most populated areas. Finally in order to ease the process of drawing conclusions from our model, we filtered the counties so only the top 20 counties with the biggest populations were viewed, we provided color to each of the clusters, and provided text to the counties.

In the second visualization we needed to show what Make of cars were most important within each of the five counties to help us make a conclusion on what charging stations should be placed where. In order to do so, we set our columns to County and Make, while setting our rows to a count of the Models. Next in our marks section we provided a colored Make, colored Model, a texted Model, and a count of the Model of car. Moving to the filters, we provided two filters to help with the easement of summarizing our findings. First we provided a filter for County to show the top 5 most populated counties that we found from our first visualization. Second, we provided a filter for the Make of the car to clean up the graph and rid it of any unneeded Makes that weren’t necessary in making our inferences.

# Interpretations 
Interpretation to question 1: 
In working with the Tableau Software and excel database we can gather that the five most populated counties of Electric Vehicles are King, Snohomish, Pierce, Douglas, and Spokane. Through visualizing this question, we have circulated the areas in which the most electric vehicles are used and our analysis yielded surprising results. 

The provided map showcases the distribution of electric vehicles (EVs) across the five counties in Washington state. Each county is colored differently to represent its name, allowing for quick identification. The map is enhanced with marks that indicate the relative population of EVs in each county, with the size of each mark correlating to the number of vehicles. The larger the mark, the higher the concentration of EVs in that county. The counties of King, Pierce, and Snohomish stand out indicating a higher population of EVs compared to other areas. This geographical representation can be extremely useful for analyzing market penetration and planning further expansion or infrastructure development specific to EV needs in the state.
![project 2 w](https://github.com/Fauz-Syed/Team-10-MIST-4610-Group-Project-2/assets/131708209/8f4c8f1f-52f1-46e1-881b-82f7b43c99b7)

Interpretation to question 2: 
The chart displays the popularity of various electric vehicles (EVs) across different counties, highlighting a strong dominance of Tesla, particularly the Model 3 and Model Y, in regions like King, Pierce, and Snohomish counties. King County shows the highest adoption of Tesla vehicles, with Model 3 leading significantly. Pierce and Snohomish also follow a similar trend with Tesla models outpacing other manufacturers. In contrast, Spokane and Douglas counties exhibit lower numbers of EVs, with a more diverse mix of manufacturers such as BMW, Ford, Chevrolet, and Nissan, though still with Tesla present. Overall, the data illustrates Tesla's significant market presence in most counties, with other manufacturers maintaining a much smaller footprint. This information is crucial for understanding the distribution of EVs and the varying degrees of market penetration by Tesla and other automotive brands across different regions. This will be helpful in determining what brand of chargers should be installed.

![project 2 graph](https://github.com/Fauz-Syed/Team-10-MIST-4610-Group-Project-2/assets/131708209/1d399037-a658-4947-a618-4d764c984b89)


# Result 
In our attempts to complete our task we have found that in the state of Washington, the Electric Vehicle capitals are King, Snohomish, Pierce, Douglas, and Spokane County. In addition we had found that within these counties, the main companies that populated these areas with EVs were Tesla, Nissan, BMW, Ford and Chevrolet. Overall, in order to maximize revenue for Electric Vehicles in the state of Washington, the five counties listed above should provide their citizens with more public charging stations from Tesla, Nissan, BMW, Ford, and Chevrolet.


