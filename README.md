# Job Portal Automation and Scrapping

The aim of this project was to extract information of all available jobs for any profile through web scrapping and automation. The data was extracted from [www.naukri.com](https://www.naukri.com/)  which provides all the data regarding jobs that is publicly available. This program provides data regarding available **job title, company, experience, pay, location and skills** required.

The project uses JavaScript libraries such as **puppeteer** to get site links and to extract data and automation. The data is then processed and converted into **json** format. Finally the json data is converted to excel data using **xlsx** library. To create and maintain folder to store the data **fs** and **path** libraries are also used.

## Installation
First of all you have to prepare your environment. Select a location where you want to store the files. I'm also on a windows machine, but you should be able to figure it out for any other platform. First you need nodejs, install it. Then, you need to install these js libraries.

    npm i puppeteer
    npm i xlsx

To run the code simply run the jobs.js file in command prompt or visual code or any other 

    node jobs.js