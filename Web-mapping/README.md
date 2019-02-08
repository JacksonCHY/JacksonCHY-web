## The NEFC Neighbourhood Public Arts Finder


### Talk a little bit about this project… 

![alt text][logo]

[logo]:https://github.com/JacksonCHY/JacksonCHY-web/blob/master/Web-mapping/Overview.png "NEFC Neighbourhood Public Arts Finder"
#### Reflective Analysis: 

Hello fellow classmates/Professor B./world! For the first time, we self-learn to create a web-map so let’s give everyone a round of applause. Here, I have a map design for people who interesting in public arts. There are probably tens of thousands public arts within City of Vancouver. However, it requires multiple personnel and consistent efforts to construct a database for all the arts establishments (but if you want to see the city-wide distribution, check out the  [Public Arts Registry](https://covapp.vancouver.ca/PublicArtRegistry/HomePage.aspx). My intention is to make a neighbourhood-specific public arts directory which can be publish on a community’s own webpage serving for local residents. I chose less popular/populated neighbourhood, the North East False Creek as the study area. It is the last stretch of the False Creek waterfront that have yet to developed, but the neighbourhood is undergoing rapid development in recent years. Users may curious the polygon features on the map. These are the land-use properties are coded with different colours as defined in the [official zoning guidelines]( https://vancouver.ca/home-property-development/northeast-false-creek.asp): 
- Parks --- green
- Vacant --- grey
- Primarily Commercial --- blue
- Primarily Residential --- yellow
- Event and Entertainment Space --- purple
- Mixed-used (commercial + residential) --- pink

Besides the function of a citizen directory, the map also allows assists urban planners to figure out where to installed additional public arts in the future development. 

I have to admit that it wasn’t an easy-peasy process for design and visualized your own idea on a website. During the map-making, I have involved in styling various map components including the font, labels, point symbols, background, land use and building eventually. Setting up the zooming features is particular important to construct an ‘information resolution’ in text labels, colour shift in background, and buildings appearance. When the map zoom out to a relatively small scale, viewers are not expecting overwhelming amount of information being present; on the contrary, the map shouldn’t lack of details as we zoom into larger scale. Reducing ‘noise’ on maps is another design principle I learned. The map creators are often deliberately hide or delete certain information in order to let viewers focus on specific subjects. For example, by get rid of the poi-label layers the graphic is cleaner and create less distraction hence my public arts symbols and land uses polygons able to stand out.

![alt text](https://github.com/JacksonCHY/JacksonCHY-web/blob/master/Web-mapping/Excerpt.png "Excerpt Of My Map")

One accomplishment/challenge I took on was adding the interactive features to the point symbols. Each single public arts establishment obtained a pop-up window that has facts about their name, artist(s), location, installed year and a brief information. Through this lab exercise, I gained further knowledge and experiences in JavaScript and HTML writing on the Atom text editor and strengthened my cartographic design skill with the user-friendly Mapbox Studio. By studying more advance coding technique as well as the Leaflet, I believe we can create more powerful and sophisticating maps as the course goes on!
Cheers!

#### Map Critiques
One of the biggest regrets in this assignment is I have yet to figure out how to add interactivity on my polygon features (i.e. the land use property). This may require further practices and knowledge exchange with like-minded peers and classmates. From the discussions with my friend Carolina and few other students, I have learned quite a bit from them as in terms of styling layers. Meanwhile, I also received some valuable feedbacks as I summarized below: 

1.	Although the original intentions are good, the context area is not large enough for further applications. 
2.	Need to fix the pop-up position of textboxes, some goes over the map boundary.
3.	The legend can be useful since the polygon interactivity is not available. 

##### Link to the map: 
https://api.mapbox.com/styles/v1/jaxsonchy/cjrs3xz2r0ati2so701sghdkj.html?fresh=true&title=true&access_token=pk.eyJ1IjoiamF4c29uY2h5IiwiYSI6ImNqcnU0cXNwczBpeHgzeW8wZ3c1MjlweW0ifQ.zucGQXtTo7fAiblD5zZiHg#15.4/49.280165/-123.105824/0
