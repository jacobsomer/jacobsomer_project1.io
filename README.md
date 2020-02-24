# Project 1 Jacob Somer
## Introduction 

 When starting this project, I was excited to chose thailand because it is one of the most beautiful and interesting countries I have ever visited. What I didn't think about was how large Thailand was. Consequently, running certain blocks of code required patience as my computer's cpu analysed 220 million grid cells. Below is the project with all of the relating infographs. 
## Thailand

![Thailand](https://github.com/jacobsomer/Workshop/blob/master/Thailand.png)

 This map of Thailand was part 1 of project 1. I found it quite straightforward in writing the code to create this image. The main difficulty I experienced with this was the region around Bangkok which is incredibly dense, and as a result, the names of the provinces are too close together. My half solution for this was to increase the scale argument in ggsave() to 4. This helped, but it was not a complete solution. 
## Thailand Population Density by Province (2020) 
<p align=center>
  Thailand in 2020
  
![Thailand](https://github.com/jacobsomer/Workshop/blob/master/Thai_pop_adm1.png)

   This infographic of Thailand proved to be one of the most interesting in my opinion. The entire country's economic production is focused around the capital. The Bangkok Metropolitan Region accounts for nearly half of Thailaind's gdp (46%) but only 8% of the country's population. This is a common sign amongst many developing nations who experience abnormally high levels of income inequality. The code for this part took a while because creating the LMIC_adm1 variable required dealing with all of Thailand's 220 million grid cells. After a solid 10 minutes of waiting on multiple attempts, my computer prevailed. 

Note: This part combines elements of part 2 and 3 just as the next segment does. 

## Thailand Population Density by Province and District (2020)
![Thailand](https://github.com/jacobsomer/Workshop/blob/master/Thai_pop_2020.png)

![Thailand](https://github.com/jacobsomer/Workshop/blob/master/Thai_adm2_bp.png)

   These two infographs combine the stretch goals of part 2 and 3. The first map is a population density map of each province and district. The bar graph shows the population of each district aggregated into each province. The greatest challenge for this part was having the right libraries activated. Occasionally R would not respond to library installs such as Tidyverse. My solution for this was to find the package that each individual command came from. For example, instead of Tidyverse, I installed tibble and ggplot2 individually as needed. 

Note: I could have combined these two infographs in the same way that they are joined for "Thailand Population Density by Province (2020)". I chose not to because I think it skews the data in the bar graph, and thus, it is presented the way it is. 
## Final Thoughts 

   Although this project was quite time consuming, I felt that my bearings on R syntax greatly improved. In conclusion, I am glad with the outcome of this first project, and I am excited as we begin the next stage of Data100!


