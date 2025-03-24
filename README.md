# Citi_Bike_Interventions
This project examines how Citi Bike usage patterns have shifted alongside changes in urban mobility driven by evolving work routines and city lifestyles.
This project provides a comprehensive analysis of bike station utilization over time by tracking the inflow and outflow of bikes at various stations. Utilizing data sets that capture both rider trips and specific interventions, such as bike relocations, we methodically calculate the net changes in bike availability at each station. Each bike arrival is recorded as an addition and each departure as a subtraction. These changes are aggregated into a cumulative count, which is then adjusted to account for the existing number of bikes at the start of the data collection period. The analysis offers insights into the patterns of bike usage and station occupancy, aiding in the optimization of bike-sharing operations and infrastructure planning. This project not only highlights temporal trends in bike station utilization but also provides a basis for further strategic enhancements to bike-sharing systems.


![image](https://github.com/user-attachments/assets/5ddf5129-d8da-4c84-b1d3-34f9fd94fce0)

![image](https://github.com/user-attachments/assets/5624b62e-fcac-4f05-8918-2518de2f70f0)

Our model has the potential to cover both overcounting and undercounting.

Potential Overcounting: Multi-rides without station return: our method might be misinterpreted as an intervention when a customer takes multiple consecutive rides without docking the bike at a station in between. Data noise: Erroneous ride records can be presented in the form of false starts or system glitches, which in reality are not matching station IDs. Potential Undercounting: Same-Station Turnarounds: we might overcount interventions if Citi Bike removes bikes for maintenance or rebalancing, but returns them to the system before another rider uses them.

Apple Maps estimates a bike ride from Inwood Hill Park at the top of Manhattan to Battery Park at the bottom to take about 1.5 hours. Citi Bike's interventions, however, involve more than just rider mobility. Here, we discuss reasons for these interventions beyond just rebalancing the bikes, based on our analysis.

**Histogram Analysis:**
The histogram reveals most interventions are brief, suggesting quick adjustments or minor maintenance. Many last under 24 hours, highlighting Citi Bike's efficiency in minimizing bike downtime. Longer interventions indicate deeper maintenance or strategic fleet repositioning.

**Maintenance and Repair:**
The data shows varying durations for interventions. Short ones likely represent quick check-ups or minor repairs, while longer durations could indicate more substantial maintenance or repairs.

**Event/Construction Relocation:**
Bikes may be relocated due to temporary events like street fairs or construction, impacting station accessibility.

**Seasonal Adjustments:**
Citi Bike may adjust operations based on seasonal variations, such as decreased usage during winter or rainy days, requiring different bike allocations.

**Incident Response:**
Damaged bikes are removed for safety reasons, contributing to the operational interventions recorded.

**System Upgrades:**
Occasional upgrades to docking stations necessitate bike redistributions to accommodate installation processes.

This comprehensive view suggests that Citi Bike's interventions are not only aimed at maintaining service balance but also at ensuring safety, responding to external events, and optimizing the overall system's efficiency and responsiveness. This analysis could be crucial for a Citi Bike analytics executive to understand the multifaceted nature of operational decisions.

![image](https://github.com/user-attachments/assets/dea52a9d-a8af-4379-a379-39151e981c46)
Our visual analysis of Citi Bike interventions employs specific visual encodings to enhance data clarity and ease of interpretation:

Geographical Placement: Dots represent each docking station in Manhattan, allowing quick location-specific trend identification.

Color Hue: Light purple, red, and yellow indicate low, medium, and high intervention counts, respectively, simplifying quick differentiation between intervention levels.

Size of Dots: Larger dots denote higher numbers of interventions, naturally drawing attention to areas with significant operational challenges.

Legend - “Intervention Count”: A clear legend correlates dot sizes and colors with intervention counts, aiding in immediate visual translation of data.

These visual choices help identify where interventions are most needed, facilitating effective resource allocation and strategic planning.


![image](https://github.com/user-attachments/assets/0b6c3bf2-e882-4edc-8cb3-22dda238fa04)






