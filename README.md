# Patch-generating Land Use Simulation (PLUS) Model software
The PLUS model is a raster-based Cellular Automata(CA) for land use/land cover(LULC) change simulation. The PLUS model integrates a rule mining framework based on Land Expansion Analysis Strategy (LEAS) and a CA model based on multi-type Random Seeds (CARS), which was used to understand the drivers of land expansion and project the dynamics of land use patches and landscape pattern.

# To cite the PLUS model
Xun Liang, Qingfeng Guan*, Keith C. Clarke, Shishi Liu, Bingyu Wang, Yao Yao. (2021). Understanding the drivers of land expansion for sustainable land use using a patch-generating land use simulation (PLUS) model: A case study in Wuhan, China, Computers, Environment and Urban Systems, 85:101569. DOI: 10.1016/j.compenvurbsys.2020.101569

# Baidu Cloud Download
link：https://pan.baidu.com/s/1xZWSZB-Z8LIKaRSCjihcbw   
code：g2xh 

# More Information
https://xungst.github.io/

# Interfaces
![add image](https://github.com/HPSCIL/Patch-generating_Land_Use_Simulation_Model/raw/master/pic1.png)
![add image](https://github.com/HPSCIL/Patch-generating_Land_Use_Simulation_Model/raw/master/pic2.png)

# Running environment
Run PLUS software by double-clicking the exe file 'PLUS V1.0_boxed.exe'. PLUS software can run independently on Windows Vista/7/8/X 64-bit environment, without any dependencies and setup process.
# User manual
Please find the attached PDF file 'User Manual PLUS -20191206-Eng.pdf' in the Repository.  
中文说明：plus模型原理和软件介绍-v2.pdf

# Test data
Please find the compressed file 'PLUS_test_data.zip' in the Repository. Land use data of PLUS model is From the study proposed by 
Liu, Su, Cao, Wang, & Guan (2019).To cite this paper:
</p>
Liu, S., Su, H., Cao, G., Wang, S., & Guan, Q. (2019). Learning from data: A post classification method for annual land cover analysis in urban areas. ISPRS Journal of Photogrammetry and Remote Sensing, 154, 202-215. doi: 10.1016/j.isprsjprs.2019.06.006  
<p>

# Innovation and advantages 
  CA model is developed to improve the representation of complex land-use and land-cover (LULC) systems. Previous studies focus on the improvement of technical modeling procedures, little researches have pay attention to promote understanding of the nonlinear relationships underlying LULC. A lack of model ability to reflect the evolution of landscape pattern and land use patches also limit the application potential of CAs for policy development. This study presents a patch-generating land use simulation (PLUS) model that integrates a rule mining framework based on Land Expansion Analysis Strategy (LEAS) and a CA model based on multi-type Random Seeds (CARS), which was used to understand the drivers of land expansion and project landscape dynamics. The PLUS model can obtain higher simulation accuracy and more similar landscape pattern than other models. The LEAS can help researchers find some underlying transition rules. The proposed method combines simulation, knowledge discovery and policy-making, which can provide vital information for both researchers and policy-makers.
 
 # Scope of application
Land use/land cover change(LULC) simulaiton, policy making, knowlege discovery for LULC, urban planning, eco-security early-warning and etc.
  
# Related open source library
  PLUS was developed purely in the C++ language. The parallel technology of PLUS software is from High-performance Spatial Computational Intelligence Lab @ China University of Geosciences (Wuhan) (https://github.com/HPSCIL). The Random forest technique in our model is from a powerful open source library called Alglib 3.9.2 (http://www.alglib.net/). The linear regression algorithm is from (https://github.com/fengbingchun/NN_Test). The UI of the software is built using a famous open source library Qt 5 (https://www.qt.io/download/). This UI provides a real-time display of dynamic changes of land use in simulation process. Moreover, the using of open source library GDAL 2.0.2 (http://www.gdal.org/) allows our model to directly read and write raster data (.tif, .img, .txt files) that includes geographical coordinate information. 
  
# Consultation 
If you have technical questions regarding PLUS software, please contact Dr. Xun Liang (liangxun@cug.edu.cn)

# Contact info
High-performance Spatial Computational Intelligence Lab(HPSCIL) (https://github.com/HPSCIL)
School of Geography and Information Engineering, China University of Geosciences, Wuhan, Hubei 430078, China.
For any possible research collaboration, please contact Prof. Qingfeng Guan (guanqf@cug.edu.cn)


