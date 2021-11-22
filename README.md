# PyBer Analysis with Matplotlib
## Project Overview
PyBer is a ride-sharing app company. They required us to create a summary DataFrame of the ride-sharing data by city type. We are going to create a multiple-line graph that shows the total weekly fares for each city type. Finally, summarize how the data differs by city type and how those differences can be used by decision-makers at PyBer. The notebook for the project located [here](https://github.com/Takomochi/PyBer_Analysis/blob/main/PyBer_Challenge.ipynb).

## Resources
- Data Source: [city_data.csv](https://github.com/Takomochi/PyBer_Analysis/blob/main/Resources/city_data.csv), [ride_data.csv](https://github.com/Takomochi/PyBer_Analysis/blob/main/Resources/ride_data.csv)
- Software: Python 3.7.10, Jupyter Notebook

## Results 
- As we can see in the Data Frame, the Urban city type has the highest number in Total rides, Total Drivers, and Total Fares. Rural city type has the lowest number in the three measurements. On the other hand, Rural city type has the highest number in Average fare per ride and Average fare per driver.<br>

<img src="https://user-images.githubusercontent.com/85041697/142748302-65aceb20-d1c7-4148-928b-76a29766123e.png" width=800>

- We can also look at the multiple-line chart below. This chart shows the total fare of each city type. The total fare is relatively consistent for each city type. Urban city type is the highest, Suburban is the second highest, and Rural is the lowest.

<img src="https://user-images.githubusercontent.com/85041697/142748385-272d9965-f392-4b11-b70b-6a13f0657073.png" width=800>


- There is huge population difference especially between Urban and Rural. Urban city type has more rides and drivers because there are more people. Average fare in Urban is low because people travel short distance. Conversely, Rural has higher average fare because people likely to travel long distance.

## Summary
### Business recommendations
In order to improve the disparities among the city types, I suggest these three recommendations.<br>

1. There is a significant amount of rides in the urban city type. So, we should raise the fare for the urban city type. 
2. People in rural areas mostly travel long distances. Lowering the price for the rural city could lead to an increased number of rides. 
3. At certain points the total fare of all city types went up probably because of spring break. We can plan to create a discount for each seasonal break since people tend to travel. 