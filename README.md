The first idea we propose is a FoodWebSite oriented to help the user to chose the best option for him/her 
showing not only the available places near his/her location using an API from Google Maps. The web site also 
will allow user to interct with the database so the website will show to the user aditional information obtained 
from the database NYC_restaurants like the grade granted, date when receive the certification and exact address.
To run the first part just run the index.html from Visual Studio or type it in the web browser.

Today September 8th just upload the modified the index.html to a index.php file because php is needed to work with
the database. In the first lines there is the php code to fetch data using the following query: 
select dba,street,grade_date,grade from nyc_restaurants where dba='tofu tofu'
In the table at the botton of the web page you will see the following information:
The restaurant name: TOFU TOFU
Street were is located: BOWERY
Date when was graded after inspection: 05/16/2023
Grade: Which letter certification was obtained, in this case A

Working in a format so user can enter information to interact with the database.

The video of the Advertise section Top5.mp4 is too big to be upload. Downloas from Slack and add it in the hosting server or PC manually.
