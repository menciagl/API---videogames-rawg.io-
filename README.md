# API INSTRUCTIONS

The following Data Harvesting project aims to use the API from rawg.io to see changes in video game trends over the last years. **To reproduce the script follow these instructions**:

1. First download the .rmd file, open it and save it into a new R Studio project.

2. Open the .rmd file and follow the instructions in the .rmd itself. **It is recommended to follow the instructions once the .rmd is opened since they are well explained there. The following instructions are just a summary**:
   
     a. **Install and load the package "dotenv" in R Studio**

     b. **Get your API key** from <https://rawg.io/>: In this web click on "API" on the upper right corner of the webpage. You'll see the button "Get API Key". Click there and register or log in the site first. Once that's done, click on "Get API Key" again. You'll see at the end a code of letters and numbers. That is your API key, copy it.
   
    c. **Save the key in a .env file**: Now, go to File on R, then New File and open a Text File. Once there you must write: TOKEN=api_key (substitute "api_key" for the series of letters and numbers you obtained on the webpage). You must save that file as ".env" in the same project folder of the script you're running. (Important: the script and the .env file have to be in the SAME PROJECT, not just in the same directory/folder)


