# Paulo's Plumbing and Heating
## Milestone Project 1 
### by Nat Thomson
---

![alt text](/README-files/multi-markup.png)

Live site: https://natthomson.github.io/mp1-plumbing/

Repository: https://github.com/NatThomson/mp1-plumbing

## Table of Contents
1. [UX](#ux)
* Purpose of Project
* User Stories
* Design Choices
  - color scheme
  - typography
  - imagery
* Wireframes

2. [Technologies Used](#technologies-used)
* Languages used
* Frameworks, Libraries & Programs Used 

3. [Testing](#testing)

4. [Addressing User Stories](#addressing-user-stories)

5. [Bugs](#bugs)

6. [Deployment](#deployment)

7. [Credits](#credits) 
* Code
* Content
* Media 
* Research
* Acknowledgements



## UX

### Purpose of Project
The purpose of the project is to create a website advertising a ficticious plumbers services. Paolo does a lot of on call work (emergency work such as leaks, burst pipes etc.) and therefore needs visitors to his website to be able to get in touch with him quickly. He also does more intricate residential plumbing work so needs to be able to showcase his work in a clear way and for potential customers to be able to get in touch with him with details of the work they need done. 
Due to the nature of the serices he provides, adults of all ages need to be able to use therefore it is imperative that the site is both user-friendly and accesible so as to appeal to as wide an audience as possible. 

### User Stories
The user will:
1. be able to easily view the website on a variety of different devices
2. be able to view emergency contact details incase plumbing services are needed in a hurry
3. be able to see services offered
4. the ability to get in contact in a variety of different ways easily and clearly
5. to navigate the various pages of the website easily
6. clearly see if services are available from the website in their area 
7. for the site to meet accesibility guidelines
8. for interactive elements to be easily useable


### Design Choices

Below is the color pallete I decided to use for the website. I decided upon this because blue is generally seen as a color which conveys a sense of calm and that's how I want the users to feel when using the website. Simple design - simple colors - calm down - call plumber. As for this pallet in particular it all comes down to that word 'simple' again. These three colors paired with an off-white shade made for a visually pleasing, un-cluttered website. 

![alt text](/README-files/screenshots/color-pal.png)

I decided to stick with one modern looking font for the website: 'Mukta' as shown below.
I used a variety of differnt font weights to help show a differnece in text importance much in the same way as font-size. 

![alt text](/README-files/screenshots/font-mukta.png)

All hero/banner images were taken from pexels using various search criteria. For the home page image I wanted a picture to show off Pablo's plumbing. 
![alt text](/assets/images/index-hero.avif)
For the contact page I wanted a picture that conveys the purpose of said page so found a n image of a laptop with an iphone in hand.
![alt text](/assets/images/contact-hero.avif)
For the testimonials page I thought an image of a could-be-Pablo would go well so users can attribute the positive reviews shown with Paolo's smiley face. 
![alt text](/assets/images/teste-hero.avif)
The final imagery to mention is that of the logo; created using DALL.E 2 - an image generating AI i signed up to use. The logo is the letter 'P' for Paolo with a dripping tap to reinforce the fact that he is a plumber. It was created by using the descriptive text of 'The letter P with a tap, digital art'. after putting it into a circle using CSS I think it looks very professional. 
![alt text](/assets/images/paolo-logo.png)


### Wireframes
index page wireframe 
![alt text](/README-files/home%20page.png)
contact page wireframe
![alt text](/README-files/contact.png)
testimonials page wireframe
![alt text](/README-files/testimonials.png)



## Technologies Used

- Balsamiq - used for creating the wireframes seen at the top of this file. 
- HTML5 & CSS3 - languages used 
- gitpod.io - only IDE I used for coding
- DallE2 - this image generating AI was used to create the logo
- Font Awesome - used for decorative icons
- pexels - source of all images on website 
- google maps - used to create the custom map
- bootstrap 4 - used for the navbar, various layouts and footer
- google fonts - source of 'Mukta' font
- imagecolorpicker.com - used to take a color from the AI generated logo and then provide an appropriate color pallete
- mycolor.space - also consulted for color scheme
- iloveimg.com - used to resoze and crop images
- avif.io - used to convert images from jpeg to avif files


## Testing

The process of testing was broken up in to three main stages: testing duri




## Addressing User Stories

Here we shall explore the user needs as outlined in the [User Stories](#user-stories) section. each user need will be examined with explanations and/or screenshots provided where appropriate 

1. be able to easily view the website on a variety of different devices

- The first step taken to insure easy viewing of the website on a variety of diffenet devices is by exploiting the 'viewport meta' tag in the head section of each of the html pages that make up the website. This helps to scale the website more appropriately on mobile devices. More information can be found on this here: https://www.w3schools.com/css/css_rwd_viewport.asp. 
- The second step taken was to make sure the website's strucure was responsive in design. I primarily used the [Boostrap Grid System](https://getbootstrap.com/docs/4.0/layout/grid/). I chose this in part because I had very recently completed the Boostrap Resume mini project so it was fresh in my mind and also because it met the requirements of the design choices I had made (as seen in the [wireframes](#wireframes)). Boostrap allowed for content to easily be switched betweem 1, 2 or 3 collumns depending on screen size and cotent. 
_see images below_
![alt text](/README-files/screenshots/shot-one-col.png)
![alt text](/README-files/screenshots/shot-two-col.png)

INSERT SCREENSHOT OF 1 VS 2 COLLUMNS

- Font size too was obviously an important consideration. Based on research undertaken it seemed clear that text should generally be of at least 16px. Therefore this is the font size used for all paragraph text. Heading text was then larger at 20px and 22px depending on content importance. These values were then converted to REM on advice from my tutor as this is seen as industry standard for text on a webpage again to aid in repsonsiveness. As a personal side note I have terible eye sight and am currently without glasses and have found no difficulty in reading any of the text content during testing. 
_see images below_
![alt text](/README-files/screenshots/shot-black-text.png)


2. be able to view emergency contact details incase plumbing services are needed in a hurry

- Oftentimes people seek to get in touch with tradeseople such as plumbers in times of desperation such as a suspected burst pipe or a backed up toilet. When this happens you want to be able to get in touch with someone that can help fast without going through the hassle of filling out a contact form and awaiting reply. This is why there is an 'Emergency Call' button located on both the index page and the contact page below each respective 'hero image'. Not only does this provide a quick solution to finding emergency contact details but the button also redirects to a href of Paolo's (actually mine) mobile number. This way a potential customer in need of emergency plumbing services can search for their local plumber, find Paolo's site, click the clearly labelled but and be on the phone to him within minutes. 
_see image below_
![alt text](/README-files/screenshots/shot-button.png)

3. be able to see services offered

- Services offered are clearly displayed on the home page under the heading 'What We Offer'. It is also worth recalling the aforementioned 'Emergency' button which in a sense is also a service and clearly dislplayed.  

_see image below_
![alt text](/README-files/screenshots/shot-what.png)

4. the ability to get in contact in a variety of different ways easily and clearly

- By following the 'Contact' link on the navbar you are taken to a page featuring brief instructions, a contact form and some other forms of getting in touch including phone number, email address and business address. The footer page also features three social media links which could also be used to get in touch should the hypothetical client wish. 

_see image below_
![alt text](/README-files/screenshots/shot-form.png)
![alt text](/README-files/screenshots/shot-social.png)

5. to navigate the various pages of the website easily

- The responsive navbar located at the top of every page allows for easy access to and from the Home, Contact and Testimonials pages. On a large screen each page name is listed horizontally within the navbar with the page you are on being clearly yet subtly highlighted by way of a darker text color. On smaller screens the navbar appears with a 'hamburger' menu which when clicked on reveals the various pages vertically. 

_see image below_
![alt text](/README-files/screenshots/shot-navbar-small.png)
![alt text](/README-files/screenshots/shot-navbar.png)


6. clearly see if services are available from the website in their area 
 
- I made a custom google map and embedded it into the home page and also the contact page to serve as an additional reminder to the user incase for instance they have googled 'newport plumber' and hoped to find a plumber in one of the 14 other Newport's in the UK. The map clearly shows a red border indicating that Paolo is happy to travel to anyone within that section of the map. 

_see image below_
![alt text](/README-files/screenshots/shot-map.png)


7. for the site to meet accesibility guidelines

A number of steps have been taken to insure the website is accessible to as many people as possible. 
- Firstly, all images have 'alt-text' describing what the image is for those that use screen readers. 
- Aria labels such as 'aria-hiiden' and 'aria-expand' have been used where appreopriate also to aid with screen readers. 
- On a simpler note the contrast between text and background colors has been chosen to be easily readable i.e. black text against an off-white background as it is in most places on the website. 


_see image below_
![alt text](/README-files/screenshots/shot-black-text.png)



8. for interactive elements to be easily useable

The website features very few interactive elements. All of them are based on common practisses found on modern websites. For example the navbar when viewed on a large screen has all pages listed horizontally. Not only this but when each is moused over the text gets visibly darker. On smaller screens the ever familiar 'hamburger menu' that (as I'm sure you will know) when clicked displays the other pages horizontally. It is worth noting too that the logo and title within the header aswell as the social media icons located in the footer are also clickable and take the user to the home page. The map on the home page and contact page is interactive. It features the same interactivity as you would find on google maps such as click and drag to move the map, mouse wheel to zoom in/out or the plus/minus buttons on the bottom left of the map and a clickable icon located in the top right of the map signifying to make the map fullscreen which when clicked opens in a new tab so as not to make the user leave the website. The 'emergency' button, which has already been discussed in previous user stories, is interactive and works by being clicked and then it will even try to call the number (my number for testing purposes).  The final interactive element is the contact form.

_see previously incuded screenshots of navbar, social links, button and form_


## Bugs 
### Fixed 
1. 
- Problem: The hamburger menu on the navbar was not collapsing/expanding.
- Solution: After some research it turned out that I had been missing the jquery script from the head section. Once that was put in it worked as intended. 
2. 
- Problem: Empty side-scrollable space on left and right side of index.html.  
- Solution: This was actually an easy fix as it had cropped up in a previous lesson on the use of bootstrap layouts. Bootstrap automatically adds negative margins called gutters. To remove them I had to add a .no-gutters class to each bootstrap row. 
3. 
- Problem: The intended background color for the navbar was appearing below the rest of the navbar.
- Solution: Removing the .bg-light class from the navbar fixed the issue. Assuption being that .bg-light has underlying styling that was contradictory to the styling I was applying to the navbar with CSS. 
4. 
- Problem: contact.html not showing updates in gitpod preview.
- Solution: Save work, commit, close it and open it again. Assuming the equivelant of clearing browser cache. 
5. 
- Problem: The navbar resizes at a differnt break-point on index.html compared to on the other two pages. 
- Solution: The pages had differnet classes. index.html was navbar-expand-md whereas the other two pages had navbar-expand-lg. The problem was righted once all three had the same attributes. This was probably caused by copying the navbar across before I had decided on the styling definate. 

### Post Deployment

6. 
- Problem: all images showing as broken img links on live website. 
- Solution: This took a little time and would have been helped by more patience on my part. At first I thought that it might be the case that the file ectensions had to be upper case for Github Pages. However this proved fruitless. My next step was to try altering the file paths from "/assets/images" to "../assets/images". This too had no effect. I then tried "./assets/images" which did not appear to work whereas in actual fact it had worked but I had been too omaptient and did not allow Pages time to load properly, assumed it had not worked and then tried the first three attempts again before finally realising ".assets/images" was correct. 

### a note on deployed website

_The three social links refresh the page instead of openning the desired website._

_The contact form too does not link anywhere but will refresh the contact page. It will however ask for required fields to be complete before allowing to submit._
## Deployment

In order to deploy this wwebsite you must go to the repository: https://github.com/NatThomson/mp1-plumbing > click on settings, located above green gitpod button > click on pages, located on left hand menu > under Build and deployment, source,  click to deploy from branch > select main branch. 
Now back in the repository, when you navigate to 'environments' on the right hand side it will say github-pages. click here and you will be taken to a page with all deployments of the website. the most recent one will be labelled active. Now click VIEW DEPLOYMENT to see the love website. 
For further information please visit: https://docs.github.com/en/pages/quickstart 


## Potential Future Development for the Website



## What I would have done diffenretly 




## Credits
### Content
- All code (unless where other-wise stated) was written by myself. The same too is to be said of the text on the webpage. 
- With the exception of the logo, all images are form pexels.com. 
 
### Personal 
Special thanks must be given to the tradespeople in my family who inspired me to design a website of this manner, my mentor Jack for his invaluble advice and contributions and my Wonderful Wife for supporting me as always. 


