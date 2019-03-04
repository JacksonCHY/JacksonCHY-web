## Public Library Finder for Public Schools in Vancouver


### What about this finder… 

![alt text][logo]

[logo]:https://github.com/JacksonCHY/JacksonCHY-web/blob/master/Interactive%20Mapping%20(Lab%202)/Overview.png "Public Library Finder for Vancouver Public Schools"
###### Figure 1. Overview of the Public Library Finder

#### Reflective Analysis: 

##### Who did I design my map for?
Through our learning in Leaflet and Turf in the past few weeks, I have produced a Vancouver Public Libraries Finder which are close to the nearby public schools. The interactive map will help thousands of parents of school-aged to find a safe space to temporarily ‘host’ (calm) their kids after school as well as for those who eagerly wish their children to develop reading habitat instead of making troubles (i.e. to neighbourhoods) before they find out when they get back from work. User-friendly is perhaps the most important “properties” for finders of various kind. This finder is very easy-to-use thus need absolutely no instruction or legend to explain. Simply click on the school, the closest library will pop-up and hopefully you kids and his/her friend will walk to there for ‘study-session’. The map is particularly useful because the Google Map sometime just can’t locate desirable ‘nearby locations’ for restaurant, gas stations…or libraries from the place you situate at. 

![alt text](https://github.com/JacksonCHY/JacksonCHY-web/blob/master/Interactive%20Mapping%20(Lab%202)/Excerpt.png "Excerpt Of My Map")
###### Figure 2. Excerpt of the Public Library Finder (Display with pop up features i.e. 'mouseover' and 'click')

##### In term of accomplishment & limitations?
In our last lab assignment, I have explored and successfully produced some degree of interactivity in the map though without a clear understanding of the rationale behind. Hence, this lab provides an opportunity to challenge myself to apply these knowledges and push beyond the limit. Two interactive features embedded are: 1) a ‘mouseover’ pop-up that display names of the point of interests; 2) a ‘click-respond’ maker that highlight the nearest library by implement the Mapboxgl.js and the Turf.js, respectively. Identify shortest path between two locations is not only crucial in ArcGIS but also in the realm of interactive cartography applications. These basic but powerful tools are common in many web maps today for spatial analysis and improve the user experience. However, some difficulties have aroused during the mapping processes and leads to some shortcoming in the final version. The symbology can be more stand out with alternative svg./png. Image other than the Maki symbols. Icons from previous mapbox.js (version 3.2.0) is preferably better in design and modifiability. It also feasible to change the maker size of libraries as you pressed the nearby school points. [My attempt]( https://jacksonchy.github.io/JacksonCHY-web/Interactive%20Mapping%20(Lab%202)/attempt2.html) is showing here but essential the turf interactivity failed to performed with the old mapbox.js code above. 

#### Collaborations and reliance on other resources
One of the biggest regrets in this assignment is I have yet to figure out how to add interactivity on my polygon features (i.e. the land use property). This may require further practices and knowledge exchange with like-minded peers and classmates. From the discussions with my friend Carolina and few other students, I have learned quite a bit from them as in terms of styling layers. Meanwhile, I also received some valuable feedbacks as I summarized below: 

Data Sources: 
1. [Vancouver Schools](http://hub.arcgis.com/datasets/80dc363cffa84820ad015fb33e456407_0).
2. [Vancouver Libraries](http://hub.arcgis.com/datasets/56825b80e6fc406988332c3a933efc31_0).
 

##### Link to the map: 
https://jacksonchy.github.io/JacksonCHY-web/Interactive%20Mapping%20(Lab%202)/index.html
