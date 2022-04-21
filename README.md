# Does Fracking Induce Earthquakes?

Fracking is the process of drilling down the Earth and injecting fluid into rocks in order to obtain oil and gas. Fracking faces a high amount of critics due to undeniably negative affects it has on the environment, especially because it disguises itself as environmentally friendly. One of these critiques is that fracking causes earthquakes, due to increasing fluid pressures within faults. This data analysis project aims to discover whether or not fracking-induced earthquakes is a major concern for the environment or not.

As a starting point to the project, basic data analysis was conducted on data of fracking projects from 2011-12. From there, it was concluded that:

1. There it little correlation between the vertical depth of a fracking project and the amount of water the project consumes. There is also little difference in the vertical depth and water consumption of gas and oil fracking operations.
 
![image](https://user-images.githubusercontent.com/77365987/164563725-80a8a4c7-591f-40dd-8601-b8bedd3eec81.png)

2. Some fracking companies are much bigger than others, and do much more operations. The top 5% of fracking corporations do more than 50% of total operations.
 
![image](https://user-images.githubusercontent.com/77365987/164563837-4ec6f59b-f8bc-42cf-b172-f4aefd1b5cd9.png)

3. While the majority of fracking is done in Middle America, some outer states such as California, Alaska, and Pennsylvania are prime spots for operations.
 
![image](https://user-images.githubusercontent.com/77365987/164564053-4d7ba4eb-13b6-48b6-bc51-7a5c35498397.png)

The next step was to analyze data for earthquakes. Two datasets were used; one held information of all 2.5+ magnitude earthquakes in 2013, and the other held info for all 2.5+ magnitude earthquakes in 1993. From there, it was concluded that:

1. There is little correlation between the depth of an earthquake and its magnitude. Furthermore, only a handful of earthquakes are explosions, rock burst, etc.. Both of these statements have not changed from 1993 to 2013.
 
![image](https://user-images.githubusercontent.com/77365987/164564500-e50193d3-977c-4693-b802-5e3494391550.png)
![image](https://user-images.githubusercontent.com/77365987/164564505-c0178bdc-fda7-4f6a-9ea2-5bd831712082.png)

2. From 1993 to 2013, more networks have been used to report earthquake locations. While 'nc' and 'ci' still remain popular, new ones such as 'tul' are being used often.

![image](https://user-images.githubusercontent.com/77365987/164565042-d9578434-e2cc-4958-8eed-b0b19429a768.png)
![image](https://user-images.githubusercontent.com/77365987/164565054-8e38b5f9-e250-401b-a586-0b9efe30a4ad.png)

3. As technology for earthquakes has progressed from 1993-2013, so have the methods for measuring magnitude. While 'ml' still remains popular, other old ones such as 'mc' have stopped being used.

![image](https://user-images.githubusercontent.com/77365987/164565450-21b38615-7bc2-4a15-b4be-1944934121a0.png)
![image](https://user-images.githubusercontent.com/77365987/164565471-4b9feb4e-c0d7-4210-be94-4fbca22a7cc1.png)

4. While in Middle America, the amount of earthquakes on average has increased from 1993-2013, in some states such as California, the amount of earthquakes have decreased.

![image](https://user-images.githubusercontent.com/77365987/164565798-ce0c08b1-69cf-47f4-a6ed-30ea4f272a6e.png)
![image](https://user-images.githubusercontent.com/77365987/164565634-923cd4ba-2568-4e12-b771-86dc41af25a6.png)

After doing basic data analysis on all of the datasets, the question of this project can finally start being answered: Does fracking cause earthquakes?
By combining the datasets in order to make a regression plot for US states for both 2011-12 fracking operations and 2013 earthquakes, it was concluded that there is no correlation between fracking and earthquakes.

![image](https://user-images.githubusercontent.com/77365987/164567838-73cd5f58-b4c9-4351-91ba-b19b8c3ade65.png)

However, this doesn't yet conclude the question. Although fracking may not directly be correlated with the number of earthquakes, it could be correlated with an increase in earthquakes. So, by including the 1993 dataset in the regression plot in order to see whether earthquake growth from 1993-2013 and fracking operations were correlated, it can also be concluded that fracking does not lead to a surge in earthquakes.

![image](https://user-images.githubusercontent.com/77365987/164568016-81bc3609-528c-4a60-805e-af47cdfb6d5c.png)

However, this conclusion was made based on earthquakes with a magnitude of 2.5 and above. Although fracking may not cause earthquakes with these magnitudes, it may cause earthquakes with a very small magnitude (0-1). So, the earthquake dataset was modified to only include information on earthquakes from 1993 and 2013 that were between a 0 and 1 magnitude. 

From there, a map was made showcasing the amount of minor earthquakes within each state. Based on the map, it is clear that fracking is not the cause of minor earthquakes, as for the majority of states with a high amount of fracking operations, there were no recorded minor earthquakes.

![image](https://user-images.githubusercontent.com/77365987/164568265-659895a1-3695-4bf0-88fd-ce4c90d84cf8.png)
![image](https://user-images.githubusercontent.com/77365987/164568293-7a5c1962-78ca-41e4-9c62-2a4ee526be34.png)

In conclusion, there is no correlation between fracking and earthquakes(even minor ones). Although fracking causes other environmental issues, the notion that fracking causes harmful earthquakes is misleading. 



