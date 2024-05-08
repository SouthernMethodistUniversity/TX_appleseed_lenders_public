# TX_appleseed_lenders_public
The public facing methodology for Texas Appleseed Payday Lenders project with Professor Spector.

## Project Overview
For the first STARs project focus, we zoomed into focusing on predatory payday lenders in Dallas. Using the licensee dataset, we were able to take these lenders and plot them on a map in relation to the evictions. We were able to plot these as stars on the maps that we generated. Additionally, we used the eviction dataset to plot the locations of all the evictions, which are depicted by dots on the graphs. 

## Methods

### Maps
One thing that we wanted to investigate with the payday lenders was the idea of a walking distance buffer around the lenders. We wanted to do this to show what eviction cases would potentially be able to walk to a payday lender, meaning it is extremely accessible to them. We defined the buffer to be 1500 meters or just under 1 mile. From this buffer map, we were able to not only see what eviction cases fall within walking distance of the lenders, but also the lenders that are in extremely close proximity with others. On the graph below, the purple dots represent the location of individual evictions, the blue stars represent the payday lenders, and the red represents the 1 mile buffer.

![Buffered Lenders with Evictions](results/bufferedlenderswevictions.png?raw=True)

From this graph, we were able to take it a step further and add in some of our Census data. We were most interested in the Income data to be able to relate income based on Census tract with the evictions and payday lenders. In this map, the base coloring (blue, green, gray, and yellow) represent the average income in the area. Dark gray is the lowest income, followed by blue, then green, then yellow, and finally the highest income with the light gray. The key on the side has a more detailed description of what incomes fall into what colors. The individual evictions are again represented by purple dots and the payday lenders are represented by green stars. Finally, the same red buffer of 1 mile is shown as well. 

![Income Map with Lenders and Evictions](results/fullmap.jpg?raw=True)

Another avenue we looked at was to graph the Total Judgment Amounts by Census block with the location of evictions. On this graph, we used a color scheme indicating that the darker the color, the more expensive the judgment. Additionally, the hatched out areas are those without judgment amount information. This map also allows us to see some of the high concentration eviction areas. 

![Total Judgment Amounts with Evictions](results/total_judgment_by_censusblk_loc.jpg?raw=True)

Finally, the last maps that we made still included the locations of the payday lenders and the evictions, but used a base indicating percent of different demographics. The ranges represent the total numbers of Hispanic, Black, White, and Total People. First, the total Hispanic population numbers. 

![Total Hispanic](results/totalhispanic.png?raw=True)

Next, the total Black population numbers.

![Total Black](results/totalblack.png?raw=True)

Next, the total White population numbers. 

![Total White](results/totalwhite.png?raw=True)

Finally, the total People population numbers. 

![Total People](results/totalpeople.png?raw=True)


