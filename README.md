1.  Concept before Compilation  
2.  Hierarchy with Harmony  
3.  Simplicity from Sacrifice  
4.  Maximum Information at Minimum Cost (after ZifF)  
5.  Engage the Emotion to Engage the Understanding 
geojson file = stateData.geojson

>Link to the Map of United States Styling [without overlay]: https://api.mapbox.com/styles/v1/alexcarl/cizqci4rq004n2rpeito7ri2c.html?title=true&access_token=pk.eyJ1IjoiYWxleGNhcmwiLCJhIjoiY2l6bWIzdzgzMDIxaTJxbDJnbGJib3o5MSJ9.cALP_wuaJJpUIBaq5SAFZg#3.8/39.325345/-103.407230/0

>Link to the Map of the United Ststes wity Styling and Responsive Overlay:
	http://students.washington.edu/adc5/Lab4_web2.html


	Before I knew what this assignment would include, I had trouble mapping the spatial data that I found so I reverted my
assignment to a simpler version.  This one just parsed the data from the website returned the data from the page.  The page
had a table with data that is pre-loaded on every map: state names, capitals, and their corresponding locations. This being
said; concept ‘before compilation’ was a bit difficult but I don’t think it negatively affected the final map.  Next, the map
follow ‘hierarchy with harmony.’  This is because the state names are capitalized, bold, of lighter color, and their letter
spacing show their higher importance over their capitals.  The capitals are not all uppercase, have less char spacing, and
have a bullet point for their locations.  Next, this maximizes information at minimum cost because it is a very simple map. 
Also, the United States is a highlighted white color so that is clearly the center of the map, as the rest of the countries
are a shade of green.  I believe this makes it easily read by the user as the point of the map.  Furthermore, it does engage
the emotion and understanding because there isn’t any emotion in the map because it is purely factual; it shows the locations
of data and nothing more. I had wanted to add more data based on the locations but I ran in to trouble with the hierarchy of
data.  My plan was to add a location for each state; e.g. Space Needle foe Washington State, Golden Gate Bridge for
California, and the Gateway Arch in Missouri.  But I couldn’t get these items to load correctly and it wasn’t part of my
simple, original dataset.

	This map is showing the contiguous US so the user understands the data is exactly that; of the United States and its
territories.  I chose this scale because it includes as much of the data without losing any readability of the map.  The next
similar but different consideration that was taken in this creation is that of its generalization.  This map has been
generalized to match its data.  For instance, it has been zoomed in to the contiguous United States so that it’s easily seen. 
If I were to zoom further out to include the other two states and the US territories, then it would be much more difficult to
read the map; at least for people with poor eye sight like myself. This revisits the idea of simplicity vs sacrifice that was
mentioned in the first paragraph of this readme.  Also, it has been zoomed out to the point that it reduces the clutter of
ever city that is included in the mapbox.gl js interface.  Next, I didn’t use any symbology for the states and instead used
border lines because this makes the states, the data, pop out much more clearly to the user; as opposed to pop up markers and
other symbols.  My ability to create the border lines was a bit above my ability at this point but not too much so I harnessed
old stackoverflow conversations; it can be found here http://stackoverflow.com/questions/29632806/using-mapbox-how-can-i-add-a-borders-layer-over-the-top-of-the-satellite-image.
I was able to overlay the javascript that I had a little help with over my personally styled map.  

	The next topic I will discuss is that of my map’s styling.  I know that the ideas behind it were touched upon in the
first paragraph, but I wanted to go over it in further specificity here.  First, I found the right latitude and longitude
location to center the United States as the start of the map on loading, these were [-100.486052, 37.830348], with a zoom
value of ‘2’.  I was attempting to use the flyto method to move from state to state, but after getting the map to fly only
between two locations, I figured that attempting this with over fifty locations is beyond my skill level on this moment in
time. 


	How to use:
	
1.Allow the map webpage to load.  

2.Hover over the target state and this will show a pop up of the data that was found for this specific location.
	

