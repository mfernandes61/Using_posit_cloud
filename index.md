## How to get set up to use Posit Clouds Rstudio in your web-browser.    
#### by Mark Fernandes (April 2026)   
1. Go to [Posit Cloud web-site](https://posit.cloud/) and click on the blue 'Get Started' button.
2. You will be asked to sign up with an e-mail address, suggested password and your First and Last name.
Alternatively you can use credentials for Google, Github or Clever if you have them.
3. If you used e-mail address you will get an email to verify your account.
4. It should now log you into posit cloud if not then use the Existing user to login e.g. with your email & password.
5. Click on the blue 'New Project' button and choose 'New Rstudio project' from the drop-down menu.
6. After a short wait you should see an Rstudio layout like the one in the course notes.   
7. __To rename your Rstudio project__ - the top line next to 'Untitled Project' tells you to click on that to rename it. Do so and choose a meaningful name.   

__Getting the example data into your cloud environment__    
In the Rstudio console, enter these two commands:    
_download.file(url="https://github.com/cambiotraining/data-analysis-in-r-and-python/raw/refs/heads/main/data.zip",
              destfile="data.zip")_   
              
_unzip("data.zip")_   
   
This should result in a data.zip file and a data folder containing the course data files being visible in the file navigator pane in the bottom right-hand pane of the Rstudio screen.   

__Downloading your R scripts onto your computer after the course__   
To download your scripts, select the files hat you wish to download by ticking the box to the left of the file name in the File navigator pane (Bottom RH pane) and then click on the little 'cog' icon labelled _more_.    
In the resulting dropdown menu click on export and then a download dialog will let you decide where the files should be stored on your computer. NB if you have selected more than one file then they will be downloaded as a zip-file.    

__Learning more about using Posit Cloud__    
[Find the Cloud documentation here](https://docs.posit.co/cloud/)    

## Happy R programming!
