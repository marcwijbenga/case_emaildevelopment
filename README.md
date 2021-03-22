# case_emaildevelopment
Case for suitsupply email development

I have written a short explanation per assignment detail so that you can understand my way of thinking in this

1.	Create a full responsible HTML file as per email design

 I started with a standard piece of CSS that I always use with emails. Because I used the <img src> I downloaded the images from the case and uploaded them to a dropbox. Then I looked for a way to use the link in the email. I changed the sharing link from /image.jpg?dl=0 to /image.jpg?raw=1. I also compiled the e-mail in codepen where I could constantly see if it was going to look good. To see what it would look like on different devices I used the "inspect" function. See screenshot. I also used litmus. If possible, I would have chosen the test send option within SFMC. For the texts etc. I always looked at the font-size, font-color and line height that were indicated within "inspect" in the case.

 I also had some trouble downloading the "social icons" such as the WhatsApp logo. So I chose to take a screenshot of the image and upload it to dropbox again and then have the image come back with the correct dimensions.





2.	Create JSON model to power the data shown in the email

First of all, I have never worked with JSON in email, so it was a nice learning experience. Since XML resembles JSON I first looked at a few variables in the email I would like to use. I first typed this out in an XML and then pasted it into the following converter: https://www.freeformatter.com/json-to-xml-converter.html.
For example, I got a JSON file that I could then parse again by means of amp script.





3.	Create AMPScript used to parse JSON created above to fill in the data in email template
 After I created the JSON file, I searched for information on stackoverflow to find out how to use the JSON in an email using AMPscript.

4.	Outline which tools you would use to aid email development in areas:
a.	translation management;

b. Responsiveness;
c. email testing.

5. Share the work using private GitHub repository. List of desired usernames will be shared later.
![image](https://user-images.githubusercontent.com/80980797/111979306-35e17f00-8b05-11eb-8cfd-3013a9de0db0.png)
