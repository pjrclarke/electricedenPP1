# Electric Eden
Electric Edens site is expressly dedicated to the fan base to help them find ways to download their latest music, find out the live dates and get in contact with any requests, queries and bookings. It'll target the people who already know who the band is and give them an opportunity to find out more relevant information.

This is the best place to discover and immerse yourself in <a href = https://pjrclarke.github.io/electricedenPP1/index.html>Electric Eden</a>.


![responsive mockup](Readme_Img/electric_eden_readme1.jpg)

# Contents

* [**Features**](<#features>)
    * [Navigation Bar](<#navigation-bar>)


# Features


## Navigation Bar ##
 
 
- The navigation bar is fixed to the top of each of the pages regardless if you scroll or not, giving the user quick, easy access to select the page they want.
- On the left we have the navigational menu. When hovering over a particular page name, the text is shadowed to help the user see which page they are about to select.
- On the right, we have the band logo that when selected will take you back to the home page.
- The colours are partially matched to the imagery to give that consistent feel across the site.


![navigation bar](Readme_Img/electric_eden_readme_nav.jpg)


## Home Page ##


- The Home Page offers the user a simple but striking visual of contrast and depth.
- The background is a blown-up view of the album artwork.
- The foreground shows the band name, links to the relevant music download sites and the full album cover nestled centrally in a white background.


![home page](Readme_Img/electric_eden_readme_landing.jpg)


## Footer ##


- The footer is fixed to the bottom of each page.
- The user is greeted with friendly and recognisable logos to help direct them to the relevant social networks.
- Copyright of the page, images, videos are all held by Electric Eden.
- The icons are brought more centrally to make it consistent with the feel of a central design.




![footer](Readme_Img/electric_eden_readme_footer.jpg)


## Media Page ##


### Video ###


- You're first greeted with a large, page size 30 second loop of Electric Edens music video, a taster, to give the user motivation to select the link to watch the full video.
- The link is nested in a slightly opaque white box with dark writing to contrast and make it easy to read.
- The link takes you to the full youtube video.


![Video Screenshot](Readme_Img/electric_eden_readme_video.jpg)


### Gallery ###


- When you scroll down, you'll find a small gallery.
- All images are bordered with a white box which helps bring it out, giving a more immersive look to the images.
- The gallery gives the user an insight to what the band does, the instruments used and the fun they have.


![Gallery](Readme_Img/electric_eden_readme_gallery.jpg)


## Live Dates ##


 ### Dates ###


- This simple and user-friendly visual gives the user access to see the dates the band are playing live.
- It has a 'more info' button for the user to use in case they want to find out more information on any particular event.
- It shows the date, venue and location of each gig.


![Live dates](Readme_Img/electric_eden_readme_dates.jpg)


## Contact


### Contact Form ###


- This contact form gives the user a simple and effective way to contact the band.
- The full name, email and message all have required fields to ensure the user has completed the necessary inputs.
- The form, once submitted is directed to a google sheet which can be easily filtered so the band can see who to contact.


![Contact Form](Readme_Img/electric_eden_readme_contact.jpg)


- The google sheet results like this;


![Google sheet results](Readme_Img/electric_eden_readme_google.jpg)


## Contact Success


### Contact Success Page ###


- This hidden page appears once the user has successfully completed the form and selected the submit button.
- It offers the user a simple way to return back to the home page.


![email success](Readme_Img/electric_eden_readme_email.jpg)


## Future features


- As this is a band page, it would need to be regularly updated with new imagery, dates and links.
- Ideally I would like to add a merchandise store later down the road.


# Testing


## Lighthouse


- During lighthouse testing the results are as follows;


## Lighthouse - Home Page ##


![Lighthouse homepage results](Readme_Img/electric_eden_readme_lighthouse_homepage.jpg)


- Performance marked down from 100. This is due to the img types. I know now that using .WebP would be a more efficient image source to use and can do this moving forward.
- 100% all other aspects.  


## Lighthouse - Media Page ##


![Lighthouse Media results](Readme_Img/electric_eden_readme_lighthouse_media.jpg)


- As expected from the homepage results, the performance has been hindered due to image file type. Something I will do in future is make sure the file type is the correct one.
- Accessibility is 100%.
- Best practice is for one image aspect ratio - Something I'll amend in future.


## Lighthouse - Live Dates ##


![Lighthouse Live Date results](Readme_Img/electric_eden_readme_lighthouse_livedate.jpg)


- Same issue above with the logo being a .png file.
- Interesting SEO considered 'More Info' to not be specific to what the user will be clicking - Which I disagree with.
- The user will clearly click on that link to find out more information about that particular event.


## Lighthouse - Contact ##


![Lighthouse Live Date results](Readme_Img/electric_eden_readme_lighthouse_contact.jpg)


- Contact form is good across the board. Aside from the consistent performance issue with the images.


## Summary on Lighthouse ##


Overall, Lighthouse testing showed 100 accessibility across the board.


## Media Screen Sizing ##


- The screen sizing adapts with each device by ensuring that the navigation flows well and the user experience is continued throughout the site.


# Validator Testing #




## HTML ##
  - No errors or issues were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fcode-institute-org.github.io%2Flove-running-2.0%2Findex.html)


 
 ## CSS ##
  - No errors or issues were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fvalidator.w3.org%2Fnu%2F%3Fdoc%3Dhttps%253A%252F%252Fcode-institute-org.github.io%252Flove-running-2.0%252Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en#css)




# Deployment


The site was deployed to GitHub pages. The steps to deploy are as follows:
- In the GitHub repository, navigate to the Settings tab.
- Select pages on the left hand menu.
- Ensured "deploy from a branch" is selected.
- Ensure the branch is set to "main" and "/root".
- Click save.
- Allow a minute.
- Refresh and the deployed link can be found at the top of the page.


The live link can be found here - https://pjrclarke.github.io/electricedenPP1/index.html


# Credits


- All imagery and videos are from Electric Eden. Some from Instagram [Electric Eden Instagram](https://www.instagram.com/electricedenband/?hl=en) and some are from their general website [Electric Eden](https://www.electriceden.co.uk). The rights to the images and videos belong to us.
- The tutors at Code Institute for helping in tough situations.
- All code is custom by myself.
- Logo created by Amy Davidson and handed ownership to Electric Eden.


## Content ##


- [Sheet Monkey](https://sheetmonkey.io/) is the third party URL used to help push the results from the form to a google sheet.
- The icons on the homepage and the footer on each page were taken from [Font Awesome](https://fontawesome.com/)
- The fonts were taken from [Google Fonts](https://fonts.google.com/)


## Media ##


- All images are owned by Electric Eden
- All videos are owned by Electric Eden


