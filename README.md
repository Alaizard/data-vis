# Overview

A data visualization of the top 100 most used words of the top 5-10 languages in each borough of NYC. Each language will have data shown about the demographics that speak the language and possibly where they live in the borough.

# MVP's

User's will be able to 
    * View the top 100 words of a language spoken in a NYC borough
    * Select from 5 different languages in that borough
    * View demographic information about that language in that borough.
    
# Wireframes

 This app will consist of a single screen with a list of the 5 NYC boroughs, allowing the user to click on one of the 5 boroughs and view the information represented. There will be nav links to my Github, LinkedIn, and AngelList, as well as an about on the project on the right. On the left there will be a list of the top 5 languages spoken in the borough that was selected. When clicked on they will display the top 100 most used words of that language in center of the screen.
 
 https://wireframe.cc/wzEe9s
 
 API and Technology
 
 D-3
 
Census.gov Language Stats
    * https://www.census.gov/data/developers/data-sets/language-stats.html
    
    
# Timeline
* 1/6/2020 - Database populated with language data. Use the census information to get the most spoken languages in each of the 5 boroughs. Then take those languages and find the 100 most used words.
* 1/7/2020 - Map functionality. Spend most of the time learning d3 and creating a map of the 5 boroughs that is interactive.
* 1/8/2020 - Individual borough information works on map click- Tie in the backend data with the frontend map so that clicking on a borough gives you the languages which you can then choose to see the top words used.
* 1/9/2020 - Demographic info works- Clicking on a burrough also lists the demographic information of that borough.
