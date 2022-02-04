# DevOps Assignment selenium grid on docker-compose
Selenium is a smart proxy server that makes it easy to run tests in parallel on multiple machines. Selenium grid is specializes in running multiple tests  across different browsers.
We can setup the grid on docker with easy cammands using docker-compose method.
# To execute this docker-compose yml file use
 `docker-compose -f docker-compose.yml up`
 Add the `-d` flag at the end for detache execution
 # To stop the execution , hit Ctrl+c, and then 
  `docker-compose -f docker-compose.yml down`
  
  Now run the below command to setup the grid.
  `docker-compose up -d`
  Now, if you go to the browser and type the url 
  localhost:4444
  Then you will see that selenium grid is running on that port and three nodes are attached with it.
