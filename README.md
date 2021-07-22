# FLS6397-Final-Project  
# Exploring Beijing Taxi Data  
  
### Reproduciblity  
1. Download the repository  
2. Open .Rmd file using RStudio     
3. Using the interactive console, install "renv" library by running `install.packages("renv")`. If already installed, skip this step.  
4. Run the following commands one-by-one on the interactive console  
```   
library(renv)
renv::init
renv::restore
```  
5. All the required libraries will be installed in the local repository in a folder named "renv". The local enviroment is automatically loaded into RStudio environment after the installation. If not, close and re-open the .Rmd file.  
  
### References:  
  
[Staypoint Identification Algorithm](https://www.microsoft.com/en-us/research/publication/mining-user-similarity-based-on-location-history/)  
[1] Li et al., "Mining user similarity based on location history". In: Proceedings of the 16th ACM SIGSPATIAL international conference on Advances in geographic information systems, 2008.  
  
[T-drive Sample Data](https://www.microsoft.com/en-us/research/publication/t-drive-trajectory-data-sample/)  
[1] Jing Yuan, Yu Zheng, Xing Xie, and Guangzhong Sun. Driving with knowledge from the physical world. In The 17th ACM SIGKDD international conference on Knowledge Discovery and Data mining, KDD'11, New York, NY, USA, 2011. ACM.  
[2] Jing Yuan, Yu Zheng, Chengyang Zhang, Wenlei Xie, Xing Xie, Guangzhong Sun, and Yan Huang. T-drive: driving directions based on taxi trajectories. In Proceedings of the 18th SIGSPATIAL International Conference on Advances in Geographic Information Systems, GIS '10, pages 99-108, New York, NY, USA,2010. ACM.  
  
[China Shapefiles](https://gadm.org/download_country_v3.html)  
License: These data were extracted from the GADM database (www.gadm.org), version 3.4, April 2018. They can be used for non-commercial purposes only.  It is not allowed to redistribute these data, or use them for commercial purposes, without prior consent. See the website (www.gadm.org) for more information.  
