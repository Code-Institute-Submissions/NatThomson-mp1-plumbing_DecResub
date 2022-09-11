# Paulo's Plumbing and Heating
## Milestone Project 1 
### by Nat Thomson
---

INSERT IMAGE OF WEBSITE ON MULITPLE DEVICES HERE

WEBSITE LINK

REPPOSITORY LINK

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
1. be able to clearly see the website on a variety of different devices
2. be able to view emergency contact details incase plumbing services are needed in a hurry
3. be able to see services offered
4. the ability to get in contact in a variety of different ways easily and clearly
5. to navigate the various pages of the website easily
6. clearly see if services are available from the website in their area 
7. for the site to meet accesibility guidelines
8. for interactive elements to be easily useable

### Wireframes
index page wireframe 
![alt text](/README-files/home%20page.png)
contact page wireframe
![alt text](/README-files/contact.png)
testimonials page wireframe
![alt text](/README-files/testimonials.png)



## Technologies Used






## Testing






## Addressing User Stories

Here we shall explore the user needs as outlined in the [User Stories](#user-stories) section. each user need will be examined with explanations and/or screenshots provided where appropriate 

1. be able to easily access the website on a variety of different devices

- The first step taken to insure easy viewing of the website on a variety of diffenet devices is by exploiting the 'viewport meta' tag in the head section of each of the html pages that make up the website. This helps to scale the website more appropriately on mobile devices. More information can be found on this here: https://www.w3schools.com/css/css_rwd_viewport.asp. 
- The second step taken was to make sure the website's strucure was responsive in design. I primarily used the [Boostrap Grid System](https://getbootstrap.com/docs/4.0/layout/grid/). I chose this in part because I had very recently completed the Boostrap Resume mini project so it was fresh in my mind and also because it met the requirements of the design choices I had made (as seen in the [wireframes](#wireframes)). Boostrap allowed for content to easily be switched betweem 1, 2 or 3 collumns depending on screen size and cotent. 
_see images below_

INSERT SCREENSHOT OF 1 VS 2 COLLUMNS
- Font size too was obviously an important consideration. Based on research undertaken it seemed clear that text should generally be of at least 16px. Therefore this is the font size used for all paragraph text. Heading text was then larger at 20px and 22px depending on content importance. These values were then converted to REM on advice from my tutor as this is seen as industry standard for text on a webpage again to aid in repsonsiveness. 

INSERT SCREENSHOT HIGHLIGHTING TEXT SIZE ON DIFF SCREENSIZES




## Deployment





## Credits
















#5C95EF
#414656
#A5ABBD colors based from complimenting colors to blue of logo image, found using mycolor.space

navbar from bootstrap 
structure on index from bootstrap

bug 1 - navbar collapse was not working in browser - FIX needed to add jquery cdn

bug 2 - space on left and right of pages not clearing - FIX needed to add .no-gutters to bootsrap rows

bug 3 - nav bar background color appearing underneath navbar on contact and testimonials pages - UPDATE fixed on testimonials page by removing 'bg-light' but same fix does not work on contact page 

bug 4 - contact page not showing updates in preview windown but is in external one - 



