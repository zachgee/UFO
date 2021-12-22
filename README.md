# UFO

## Overview

The purpose of our project is to help out friend Dana create a dynamic HTML page using Javascript and bootstrap in order to organize through a javascript data file all focused on.... ALIENS!!! Dana has a passion for aliens and access to a javascript file with a ton of information on our extrterrestrial friends(or foes). With our help, Dana will have an HTML page that utilizes filters in order to sift through all of the information and learn more about peoples encounters with E.T.'S. 

## The Truth is Out There

![ttiot](https://user-images.githubusercontent.com/87949792/147021628-89ff0fff-b8c4-4e3c-97a9-c3ec482bd75c.png)


Above is an image of what a user will see when visiting this page. We helped Dana create an organized, aesthetically pleasing page. 

## Filters 


![Screenshot (83)](https://user-images.githubusercontent.com/87949792/147020215-1a0ca513-b659-4ff3-84b2-b623c6084bc6.png)



After importing the data Dana provided to us (this can be found in this repo in data.js) and organizing some colums for Dana, we had created a table with all of the data in data.js. The unfiltered table can be seen in the image above. This screenshot does not due the table justice, as it is quite extensive. To help individuals sort through this data, we created filters that can sift through the data, dependning on the user entereing the date, city, state, country and shape of the ufo they are interested in. As well, a user is able to filter through multiple criteria simultaneously. Below is an image of what it would be like to filter the date for 1/13/2010:


![Screenshot (84)](https://user-images.githubusercontent.com/87949792/147020631-9ce365f4-de2f-4d86-84ae-10b8955e6c3d.png)


The next image is what it would be like if a user filtered only by state, and entered "tx"


![Screenshot (85)](https://user-images.githubusercontent.com/87949792/147020789-4ec3cae5-cee3-41f3-8131-cd2146e9ead0.png)


The final image shows the results for someone using two search criteria simultaneouslt: "1/8/2010" for the date and "tx" for the state:


![Screenshot (87)](https://user-images.githubusercontent.com/87949792/147020931-d6475f14-0b42-41c0-98c1-464467c75b4a.png)


Finally, if someone wants to reset the data, they can just scroll back up and click on the "UFO Sightings" Button:


![Screenshot (82)](https://user-images.githubusercontent.com/87949792/147021416-62b97ad9-859e-4323-a2ed-52871862ed75.png)


## Summary

Overall, the website is something Dana should be proud to show off! However, nothing comes without criticism. One drawback of the design is that if one is not familiar with the data, they may not know what to enter while searching. For example, the data's dates are limited to a couple of weeks in January of 2010. If the user searched for a date outside of Janurary 2010, they will see 0 results and may think there is something wrong with the page. I propise two updates to make the page more user friendly:

    1) For each search bar, insert a drop down menu that contains the avaiable items for each search criteria. 
    2) Make the drop down menus dynamic - for example if one filters the date for "1/1/2010", than the drop down menu for "city" should only include cities that have  information on that date.

