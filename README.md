# SimiYPlotter21
##### #Javascript # d2c-js* #plotter  #console_vs_document #purely_costumized-javascript #plotly.js # handsometabel.js
#### d2c-js ( document to console coding style) 
##### good for newbees for purly costumized javascript
   A form of javascript coding that avoids the console function for backend computations
   all functions take input from
   
     document.getElementById( ......
   
##### template 
In this repo under: sourcce/d2cTemplate_00_index.html
###### template structure

###### template imports:
       - a exelesque library 
       - a regular plotter
### Older Text
#### Step 1 

     Provide a javascript file with the desired JSON objects
              iTHTM.js -> daObJ0 :: Object
                          daObJ1 :: Object
  
 #### Step 2  
     Manually switch and select in objects
              index.html
              
              type e.g> GET 2 flist2 CAT 2 dataStr11 

 
 #### Step 1 Detailed                         
              const obJ0 = {"flist1":"40.1496259351621,47.93926247288503,50.81967213114754,62.0253164556962",
                            "flist2":"64.97816593886463,59.73799126637555,57.37991266375546,44.80349344978166",
                            "flist3":"30.139372822299652,19.686411149825783,14.982578397212542,9.177215189873417",
                            "flist4":"29.649122807017545,19.12280701754386,14.385964912280702,9.81012658227848",
                            "flist5":"39.15211970074813,47.07158351409978,50.0,61.392405063291136",
                            "flist6":"23.18007662835249,11.685823754789272,6.513409961685824,17.40506329113924"};

             const obJ1 = { "dataStr11" : "48.05194805194805,59.65065502183406,19.51219512195122,18.94736842105263,47.18614718614719,11.49425287356322",
                            "dataStr12" : "51.21951219512195,57.030567685589524,14.285714285714285,13.68421052631579,50.40650406504065,5.74712643678161",
                            "dataStr13" : "67.21311475409836,36.06986899563319,21.584699453551913,22.131147540983605,66.66666666666666,28.688524590163933"};

              daObJ0  = new Object(obJ0); 

              daObJ1  = new Object(obJ1); 

              const dataStr0 = (daObJ0.flist1); //"40.149, 47.939, 50.819, 62.025"; 
              const data00 = (""+dataStr0+"").split(","); //["40.1496259351621","47.93926247288503","50.81967213114754","62.0253164556962"];
              const data0 = (""+dataStr0+"").split(","); //["40.149","47.939","50.819","62.025"];
              const thu2Ar = ["B Byz","B B60","B B","B B","D N","F N"];
              
 #### Step 2 Detailed             
