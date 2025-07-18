# ESE6800-SRAM Evaluation

The goal of this project was to evaluate various SRAM Designs in their individual cell operation and whole array operation. We discovered that there are various benefits and drawbacks of the different designs which designers must be aware of when using different implementations. 

The 6T SRAM is a well studied design and is commonly used for fast access memory. However, there are limitations to it due to sizing and the number of transistors used. Other designs such as 7T, 8T, 9T, and 10T exist, however they perform differently and require more physical space. We evaluate individual cell operation for all five cells and overall array operation for the 6T, 9T, and 10T cells to understand each design’s benefits and drawbacks. We find that 7T, 8T, and 10T show significant improvement in the SNM-R. We also find that the 10T cell allows for a significant energy reduction relative to the 6T cell in a basic 8 by 8 array, while the 9T cell introduces additional bitline capacitance and peripheral complexity that results in increased energy consumption.

Our final report and presentation is included in this repository. Additionally our Cadence GPDK design files are available. 

This project was done in collaboration with William Hatfield. 
