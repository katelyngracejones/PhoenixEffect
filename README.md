This code analyzes data from quantitatively scored mortality images for Porites compressa and Montipora capitata colonies at Kane'ohe Bay, HI, USA from 2015 to 2022. These corals experienced two marine heatwaves in 2015 and 2019 and were marked as bleaching-susceptible in 2015. Each image was scored through ROIs drawn in ImageJ, and this code sums the areas of dead and live tissue on each individual image. Gaps in the time series within each colony tag are due to either a lost colony (from overgrowth/coverage of the tag or limitations in accessing the reef area) or poor image quality/clarity. The goal of this code is to track the specific mortality of each colony over time and observe if the Phoenix Effect takes place in these resilient corals. 

- ROI = Region of Interest
- TotalArea and DeadArea both have the units of pixels squared
