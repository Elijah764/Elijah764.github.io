# Elijah764.github.io
# Phone Call History App
#### Video Demo:  <https://youtu.be/nBfPP_tII7g>
#### Description: 
This app is made to help a call center record phone numbers and the result of the call.
When I initially started this project it was a favor for a friend. But later it turned to the app that it is today. At first i thought I would make it a desktop app and that I would have to send a zip file with a empty file to act as a database. But then I looked into website hosting and realized it was the better choice.

One of the main reasons web hosting was better was because we could access the app on our phone too.Also they could use the same database and have shared data removing the possability of two people calling the same number. I thought that in order to host a app on github pages the website could only be one file... I was wrong. But it works it used axios, javascript, html, and Css.

The way the app works it that it used the website as the user interface and the database(the google sheet) has javascript code to help with the post and get request sent to it. So to login I promt the user for a password now doing that they can put in whatever and can still access the website but the main functions are not accessable and when u put in the wrong password and try to do something you are promted again till you put the right password. After you log in you are able to search, generate, and remove phone numbers and there results. The phone numbers are sent to the database as hash values and then we are able to search for them if they exist. 

The first 6 number always stay the same till the database if filled without 500 numbers we did the math and theres about 500+ diffrent number possablities. So at 500 I manualy change the middle 3 numbers do go onto the next set of 500+ numbers. I dont delete the the first 3 so that we use the same area code. I started this project ages ago then I learned about CS50 and it funny because this hole project is in javascript and CS50 had one section with Javascrip but oh well. 

The way the website was designed was to be entertaining. When i first made the app i just had a simple blue and white backround but then my friend looked at it and said it looked boring. So I knew he liked surfing so i looked up how to make a css wave. Then I also wanted the cursor to do something so I looked up how to make a cursor into a emoji and the easiest way to do it without adding a file was thorugh javascript. I was trying to make a cheese wheel loading thing. But I could not find a css cheese wheel. The version you would be using it the working version that been on github and is live at https://elijah764.github.io/ . The reason im not giving you the most current version v5 is beacuse im trying to impelent a language feature and its not fully working so if I finish that soon ill send that in. But if you are reading this cannot choose a language that why. 
Enjoy!
