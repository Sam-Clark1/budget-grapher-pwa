

  <img src="https://img.shields.io/badge/license-MIT-blue" alt="badge"></img>
  
# budget-grapher-pwa

## Description
An application that utilizes node.js, express.js, and MongoDB to generate a website (deployed on Heroku) that allows the user to track their finances by adding and subtracting funds. Visually shows these processes with a graph. Is usable offline by using indexDB to store inputs and will automatically add them to the database when internet connection is restored. Website can be downloaded as a Progressive Web App(PWA).
## Table of Contents
1. [Usage](#usage)
2. [Screenshot](#screenshot)
3. [License](#license)
4. [Contributing](#contributing)
5. [Tests](#tests)
6. [Questions](#questions)

## Usage
You can visit this site here: https://budget-grapher.herokuapp.com </br>
To make a transaction, add a name for the transaction and then a transaction amount. Once done, you can add or subtract that amount from your total. A graphical representation of your total money over time will be displayed when transactions are made. To download as a PWA, open website in Google Chrome and click the install icon in the url box.

## Screenshot
<img src='./public/icons/screenshot.png'>

## Contributing
Not looking for contributions at this time.

## Tests
To test the offline capabilites, open the website in Google Chrome and open the developer tools. Go to the network tab and click the drop down box that says "no throttling" and choose "offline". Then, make a transaction and you should see the website behave normally. Change it back from offline to "No throttling" and a message should pop up saying the stored data was added. 

## Questions
If you have questions, you can email me at samclark2399@gmail.com or you can checkout my repos
on my <a href=https://github.com/sam-clark1>GitHub</a>.


  ## License
  Licensed under the 
  <a href=https://github.com/microsoft/vscode/blob/main/LICENSE.txt>MIT</a>
   license.
  

