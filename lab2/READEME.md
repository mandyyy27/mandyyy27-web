Title: Earthquake distribution and value and magnitude
![WechatIMG1043](https://user-images.githubusercontent.com/123501855/228759579-4d2a1456-9eec-4846-b69b-341e3a162f90.png)

This map is for anyone interested in maps and earthquakes, and as a resident of the West Coast growing up, I have always been highly interested in earthquakes and seismic zones. However, I am not sure of the exact frequency and magnitude of earthquakes.

In order to clear up the last data bias issue, I learned some python tricks to clean up the data from my computer science classmates, and although it was not proficient and took a large portion of my time, it was extremely helpful in organizing the data for this map.

The dataset is from: https://www.kaggle.com/datasets/garrickhague/world-earthquake-data-from-1906-2022

My original plan was to mark the approximate outline of the seismic zone on this map as well, or set the seismic zone section to be shaded. The viewer would not look into the causes of the earthquakes and would not study the terrain structure. Instead, we take it for granted that earthquakes should occur here. Therefore, we remove the marker of the seismic zone, although the final map looks like it is highly coincident with the seismic zone.

<img width="452" alt="marker" src="https://user-images.githubusercontent.com/123501855/228761968-b27a6e90-6e13-40f1-8e38-8d7d18003536.png">
<img width="158" alt="marker2" src="https://user-images.githubusercontent.com/123501855/228762031-efd36156-91bf-4ed9-a9f8-0760fd622167.png">

Also, in addition to the two boxes of interactive (year & magnitude), I added a blue pin that can be dragged and dropped in order to allow the viewer to better explore the specific data and information of an area that has frequent (or infrequent) earthquakes. The viewer can drag the blue pin to any location on the earth to explore the cumulative number of earthquakes in the past decade.

In terms of design, when people mention earthquakes, they usually associate a lot of disaster and heavy images. But I chose a relatively ordinary and relaxing blue as the main color. The reason is that besides the huge type of earthquakes, there are also many small earthquakes that people do not feel and do not have a huge impact on their lives, and everyone feels small earthquakes differently (for example, when I lived in California, I would hear my friends say that there was an earthquake every month, but I never felt it myself for 4 years). So I hope that people can look at earthquakes and the reasons behind them, and that, like other studies, this is just a common map, not a symbol of disaster.
