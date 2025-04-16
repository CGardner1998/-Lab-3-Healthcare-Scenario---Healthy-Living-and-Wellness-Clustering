Evaluation Metrics
                     Model  Silhouette Score  WCSS (KMeans only)
0        KMeans (Original)          0.151616          740.466268
1             KMeans (PCA)          0.151616          740.466268
2  Hierarchical (Original)          0.136285                 NaN
3       Hierarchical (PCA)          0.136285                 NaN
 
Dataset Summary
       Exercise_Time_Min  Healthy_Meals_Per_Day  Sleep_Hours_Per_Night  \
count         200.000000             200.000000             200.000000   
mean           29.592290               2.875000               6.933582   
std             9.310039               1.815449               1.422471   
min             3.802549               0.000000               1.778787   
25%            22.948723               2.000000               5.967243   
50%            29.958081               3.000000               6.972331   
75%            35.008525               4.000000               7.886509   
max            57.201692               9.000000              10.708419   

       Stress_Level         BMI  KMeans_Cluster  Hierarchical_Cluster  \
count    200.000000  200.000000      200.000000            200.000000   
mean       4.995000   25.150008        1.150000              0.745000   
std        2.605556    5.070778        0.755216              0.801992   
min        1.000000   12.502971        0.000000              0.000000   
25%        3.000000   21.458196        1.000000              0.000000   
50%        5.000000   25.155662        1.000000              1.000000   
75%        7.000000   28.011155        2.000000              1.000000   
max        9.000000   37.898547        2.000000              2.000000   

       KMeans_PCA_Cluster  Hierarchical_PCA_Cluster  
count          200.000000                200.000000  
mean             1.150000                  0.745000  
std              0.755216                  0.801992  
min              0.000000                  0.000000  
25%              1.000000                  0.000000  
50%              1.000000                  1.000000  
75%              2.000000                  1.000000  
max              2.000000                  2.000000  
 
 

 
