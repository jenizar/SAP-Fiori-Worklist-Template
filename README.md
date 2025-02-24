The tutorial assumes that you have a free Heroku account (Heroku CLI installed), git installed, and that you have Node.js and npm installed locally.

# Run localy

To run this yourself, do the following steps:

1. Clone this repo with `git clone https://github.com/jenizar/SAP-Fiori-Worklist-Template`

2. Setup the dependencies with `npm install` (make sure you are in `SAP-Fiori-Worklist-Template` directory)

3. `npm start`

4. Open http://localhost:5000/webapp/ in yoiur favorite browser.

# Deploy to Heroku cloud

$ heroku login

$ heroku create jenizar-sapui5-worklist

$ git push heroku main

$ heroku open

--> if problem use:

$ git remote rm heroku

$ heroku create jenizar-sapui5-worklist

$ git push heroku HEAD:master

Note:

- jenizar-sapui5-walkthrough is name your apps in the url, example: https://jenizar-sapui5-worklist.herokuapp.com

- It automatically open your browser and add /webapp in the end of url.

- It utilize nodejs buildpack

# Live

https://jenizar-sapui5-worklist.herokuapp.com/webapp

# Video Tutorial

[![IMAGE ALT TEXT HERE](http://img.youtube.com/vi/DRRKz_u5KXU/0.jpg)](http://www.youtube.com/watch?v=DRRKz_u5KXU)

![alt text](https://github.com/jenizar/SAP-Fiori-Worklist-Template/blob/master/Screenshot/Screenshot%20from%202021-12-19%2016-19-23.png)

![alt text](https://github.com/jenizar/SAP-Fiori-Worklist-Template/blob/master/Screenshot/Screenshot%20from%202021-12-19%2016-19-27.png)

References:

1. https://github.com/jenizar/heroku-sapui5-mockd-internal

2. https://github.com/jenizar/sap-ui5-walkthrough

3. https://github.com/jenizar/heroku-sapui5-covid19-tracker


# Cadaxo SAP Fiori Worklist Template

This is an SAP Fiori Example app which follows [SAPUI5 Developer Guidlines Worklist Template standarts (https://sapui5.netweaver.ondemand.com/#docs/guide/a77f2d29299247f8a3e30226507b1765.html)

(Today - 10th of Nov 2016 - still some parts are missing to meet the Worklist Template standarts - I am still working on it :)

# Author
Dusan Sacha, dusan.sacha@cadaxo.com

Cadaxo, www.cadaxo.com

# License

Copyright © 2016 Dusan Sacha

This project is licensed under the MIT license.
