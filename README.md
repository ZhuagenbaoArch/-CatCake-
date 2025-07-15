![2](https://github.com/user-attachments/assets/2fe16898-f8ed-4513-bb42-39e31c101492)  
# -CatCake-
Grasshopper插件，可下载Mapbox等高线和高清地图，还可以看可爱的三月七猫猫糕.  
grasshopper plugin, you can download Mapbox contours and HD maps, and you can also see the cute March 7 CatCake

![1](https://github.com/user-attachments/assets/f6ab64fe-b126-4088-8ed2-73ff4d35b336)  
插件简介,现在是V0.1版本，只有2个实用功能，最主要还是三月七的猫猫糕足够可爱，上班时看一看，就当撸猫了.  插件的LOGO图片需要的可以去米游社我发布的帖子下下载，希望能给个赞(https://www.miyoushe.com/ys/article/66172104).  
Plug-in introduction,It's now V0.1 version,There are only 2 practical functions,The most important thing is that the March 7 CatCake is cute enough.  
If you need the logo pic of this plugin, you can go to the Miyou Club to download it under the post I posted before, please give a thumbs up (https://www.miyoushe.com/ys/article/66172104).

插件现有功能介绍：  
Introduction to the current functions of the plugin:  
![3](https://github.com/user-attachments/assets/7888d556-8090-4a73-a7f2-0009ea6f9be6)
![4](https://github.com/user-attachments/assets/fd57dd1d-622e-4864-8a1d-a25e9149ae0a)  
下载等高线示意，上方等高线是真实高度（单位请设置为米），下方是每个瓦片对应的大小.  
MapboxTerrainDownloader: Download and process the MVT format tiles of MapboxTerrain v2. By entering the longitude and latitude, as well as the required zoom level and range radius, obtain the contour lines, range and position information of each tile within the selected range (the range is rectangular) (please set the unit to meters). You can choose to output the true size (consistent with the actual geographical range size: the higher the dimension, the smaller the individual tile) or the Mercator projection size (the tile size does not change with the height of the dimension, but is equal to the tile size at the equatorial position under this zoom level. Therefore, the higher the dimension, the greater the dimensional distortion.

![5](https://github.com/user-attachments/assets/bcb0bc11-2d89-406c-b3e2-419208104b8d)
![6](https://github.com/user-attachments/assets/c748a61d-93fb-489f-84a3-ae843eba00e0)  
MapboxImageryDownloader：下载Mapbox Satellite地图到指定位置。通通过输入经纬度和所需的zoom level 与范围半径，得到所选范围内（范围为矩形）的所有瓦片图像并自动拼合。可选择图片格式（jpeg或png)和图片是否需要高清格式.    
MapboxImageryDownloader: Download the Mapbox Satellite map to the specified location. By inputting the longitude and latitude, as well as the required zoom level and range radius, all the tile images within the selected range (the range is rectangular) are obtained and automatically combined. You can choose the image format (jpeg or png) and whether the image needs to be in high-definition format.  

插件需要使用者申请MAPBOX账户（网站有免费额度，够用），申请后可得到下载需要的access token.  
The plugin requires users to apply for a MAPBOX account (the website has a free quota, which is sufficient). After applying, users can obtain the access token needed for downloading.  
