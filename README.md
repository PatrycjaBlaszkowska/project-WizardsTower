# Wizard's Tower

[Link to a live site](https://patrycjablaszkowska.github.io/project-WizardsTower/)

![Responsive view of Wizzards Tower website](https://github.com/PatrycjaBlaszkowska/project-WizardsTower/blob/main/docs/images/introduction-image.PNG)

## Introduction

Welcome to my first project, part of the Code Institute Full Stack Development Course. The purpose of this project is to build a responsive website using HTML, CSS, and Bootstrap (optional) only.

The Wizard's Tower is a project for a fictional magic-themed cocktail bar inspired by potion brewing classes in the Harry Potter movie.

Users will be able to navigate through the website using a functional navigation bar. Wizard's Tower will offer for the user to see what the purpose of the business is on the home page.
The user will also be able to see a menu of cocktails being served as well as contact the business via the contact form on the dedicated page.


#### Thank you for visiting Wizard's Tower

## UX - User Experience Design

A user experience designer, Jesse James Garrett, introduced five UX design elements in his book The Elements of User Experience.
In the book, he explains the steps of user experience projects and what UX designers should consider at each stage.
This is where most of my planning process steps came from.

The 5 planes of UX are as below:

- The Strategy Plane
- The Scope Plane
- The Structure Plane
- The Skeleton Plane
- The Surface Plane

## The Strategy Plane

### Creator Goals

- As a creator, I want webpage to be easy to navigate.
- As a creator, I want webpage to be a user-friendly and responsive.
- As a creator, I want users to be able to see what the business has to offer immidiately (on a home page).
- As a creator, I want users to be motivated to book activities being offered by business and/or book a table after visiting a webpage.

### User Stories

- As a user, I want to be able to navigate across the site to see different pages on a webpage.
- As a user, I want the purpose of a webpage to be clear so I can decide if the content is right for me.
- As a user, I want to see the available activities and drinks menu.
- As a user, I want to be able to contact the business either via phone or online.

**User stories are based on online research, personal experience, and my relatives experiences.**

## The Scope Plane

I thought of the features I wanted to implement before designing the project, and a few of them were not achievable within my deadline. I decided to implement the ones covering my user stories first and add the remaining features later.

**Features implemented upon webpage release**

- Home Page with an introduction and business opening times.
- Functional navigation bar, allowing users to navigate to different pages.
- Menu page allowing users to see a menu of drinks being served.
- Contact page allowing users to fill out a form and contact a business to either provide a feedback, ask questions or/and request a table or activity reservation.
- A button to take the user back to the home page after filling out contact a form.
- Footer with an address, contact details, and links to social media.
  
**Features planned to add later**

- A feature for booking a table to separate it from a contact form, which will be added to a home page.
- A feature that will send a user an e-mail confirmation after making a reservation or filling out a contact form.
- An additional section showing customer reviews from Google. This will also be added to the home page.
- An additional page for a photo gallery containing photos from activities like potions brewing.

##### *Above decisions have been made based on below table.*

| Feature       | Feasibility   | Importance    |
| ------------- |:-------------:|:-------------:|
|Navigation     | 5             | 5             |
|Introduction   | 5             | 5             |
|Opening times  | 5             | 5             |
|Drinks Menu    | 5             | 5             |
|Contact page   | 5             | 5             |
|Social media   | 5             | 5             |
|Book table btn | 5             | 4             |
|E-mail conf    | 4             | 4             |
|Google reviews | 4             | 4             |
|Photo gallery  | 5             | 4             |

## The Scope Plane

### Colors

#505253 :
- Main background
- Navigation bar
- Footer
- Buttons

![#505253 Hex Color](https://github.com/PatrycjaBlaszkowska/project-WizardsTower/blob/main/docs/images/%23505253.PNG)
  
#000 :
- Background of some sections
 
![#000 Hex Color](https://github.com/PatrycjaBlaszkowska/project-WizardsTower/blob/main/docs/images/%23000.PNG)

#FAFAFA :
- Text
- Borders
- Icons

![#FAFAFA Hex Color](https://github.com/PatrycjaBlaszkowska/project-WizardsTower/blob/main/docs/images/%23FAFAFA.PNG)

#EBE5E5 :
- Footer text
- Social links
- Icons

![#EBE5E5 Hex Color](https://github.com/PatrycjaBlaszkowska/project-WizardsTower/blob/main/docs/images/%23EBE5E5.PNG)

### Fonts

Both fonts used in this project are Google Fonts.

#### Roboto :

- I used Roboto as the main font, as it's one of the most popular and user-friendly fonts. The Roboto font is easy to read even on the smallest devices and provides a positive user experience.

#### Exo :

- Exo font has been used for some headings but also for a navigation bar and menu section. Using a different font for these features helped me highlight important sections to user and made the website easier and quicker to navigate.

### Images

All images used in this project have been downloaded from:

- Pinterest
- Pixabay
- Unsplash
- Wallpapercave 

##### *More information in credits section.*

## The Skeleton Plane

I made some significant changes to my project. Some features have become unnecessary or have caused poor user experience, so I decided to remove them.

[Home page wireframes](https://github.com/PatrycjaBlaszkowska/project-WizardsTower/blob/main/docs/wireframes/home.pdf)

- I used a different hero photo for mobile devices with a width of the screen under 992 pixels, as the original photo was too big and looks unattractive when scaled.
- I also made most content appear in two columns on the desktop instead of one for a better user experience.
- The navigation bar has been moved to the left side on the mobile devices to provide some space between it and a logo. I made this decision to keep the navbar tidy and more user-friendly.
  
[Menu page wireframes](https://github.com/PatrycjaBlaszkowska/project-WizardsTower/blob/main/docs/wireframes/menu.pdf)

- Removed hero photo both from desktop and mobile view as it was taking users attention away from the content. 
- The menu is appearing in two columns on the desktop instead of one, as it's looking more practical. It's also filling up empty gaps that were looking unattractive on the desktop.
- The menu page has an additional section for upcoming cocktails for both desktop and mobile devices. I decided to add it after doing my research through websites in the hospitality industry.
- The navigation bar has been moved to the left side on the mobile devices to provide some space between it and a logo. I made this decision to keep the navbar tidy and more user-friendly.
  
[Contact page wireframes](https://github.com/PatrycjaBlaszkowska/project-WizardsTower/blob/main/docs/wireframes/contact.pdf)

- Removed hero photo both from desktop and mobile view as it was taking users attention away from the content.
- I decided to change the appearance of the contact form after doing my research. According to the information I obtained, the contact form I decided to use instead is more user-friendly and looks better.
- The navigation bar has been moved to the left side on the mobile devices to provide some space between it and a logo. I made this decision to keep the navbar tidy and more user-friendly.

## The Surface Plane

### Features present across the project 

### Navigation bar :

- Navabar is present on every page, fully responsive across all resolutions.
- Navbar toggles to a hamburger menu on mobile devices. 
- The user can navigate across the site freely.

**Desktop** : 

![Desktop navbar](https://github.com/PatrycjaBlaszkowska/project-WizardsTower/blob/main/docs/testing/navbar-desktop.PNG)

**Mobile** :

![Mobile navbar](https://github.com/PatrycjaBlaszkowska/project-WizardsTower/blob/main/docs/testing/navbar-mobile.PNG)

### Footer :

- Footer is present on every page, for the user who wishes to navigate to the pages from the bottom, rather than having to scroll up.
- Footer contains social media links that are opening in a new tab.

![Footer](https://github.com/PatrycjaBlaszkowska/project-WizardsTower/blob/main/docs/testing/footer.PNG)

### Hero images :

- Included to draw the user's attention and show the purpose of the website stright away.

**Desktop** :

![Hero image desktop](https://github.com/PatrycjaBlaszkowska/project-WizardsTower/blob/main/docs/testing/hero-image-desktop-feature.PNG)

**Mobile** :

![Hero image mobile](https://github.com/PatrycjaBlaszkowska/project-WizardsTower/blob/main/docs/testing/hero-image-mobile-feature.PNG)

### Introduction section :

- The introduction section shows the purpose of the business right away, so the user can determine if this website is useful for him within the first few minutes.

![Home page - introduction](https://github.com/PatrycjaBlaszkowska/project-WizardsTower/blob/main/docs/testing/homepage-potions.PNG)

### Activities section :

- The activities section on a home page shows all services offered by Wizzards Tower and encourages the user to contact the business.

![Home page - activities](https://github.com/PatrycjaBlaszkowska/project-WizardsTower/blob/main/docs/testing/homepage-activities.PNG)

### Menu section :

- Menu section contains information about all cocktails and mocktails business is currently serving. 
- The user is also informed about new cocktails coming shortly.
- This section also includes video showing new cocktails to encourage users to visit Wizzards Tower.

![Menu](https://github.com/PatrycjaBlaszkowska/project-WizardsTower/blob/main/docs/testing/menu.PNG)

### Contact form :

- Allows users to contact businesses with any inquiries.
- The user is also able to book activities or a table via a contact form.
- The user is able to provide feedback to the business. 

![Contact form](https://github.com/PatrycjaBlaszkowska/project-WizardsTower/blob/main/docs/testing/contact-form.PNG)

## Technologies Used

- [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)
- [Github](https://github.com/)
- [Git](https://git-scm.com/)
- [Bootstrap 4.6](https://getbootstrap.com/docs/4.6/getting-started/introduction/)
- [jQuery](https://jquery.com/) - Used with Bootstrap.
- [JavaScript](https://www.javascript.com/) - Used with Bootstrap.
- [Hover.css](https://ianlunn.github.io/Hover/)
- [FontAwsome](https://fontawesome.com/)
- [Balsamiq](https://balsamiq.com/wireframes/?gad_source=1&gclid=Cj0KCQiAy9msBhD0ARIsANbk0A_UrgDIhg_KSUHNCOUn-D9DiHl_9Z1dwScGRuI4JET1bnKbQkqwSb8aArFqEALw_wcB)
- [Code Anywhere](https://app.codeanywhere.com/)
- [Google Fonts](https://fonts.google.com/)
- [QuillBot](https://quillbot.com/)
- [Google Developer Tools](https://developer.chrome.com/docs/devtools/)

## Testing

### User stories :

[User stories testing](https://github.com/PatrycjaBlaszkowska/project-WizardsTower/blob/main/docs/testing/testing.md)

### Manual testing

- Navigation bar :
    - Navigation bar is fully responsive on large/medium/small resolutions.
    - Navigation bar toggles to a hamburger menu on mobile devices and stays fully responsive.
    - All links to pages are working properly.
    - Hover CSS is correctly working. (Available on desktop only)

- Footer :
    - Footer is fully responsive on large/medium/small resolutions.
    - Social media links are working and opening in a new tab.
    - Links to pages are working properly.
    - Hover CSS is correctly working. (Available on desktop only).

- Hero image :
    - Image is succesfully changing for a different on on devices smaller than 922px.

- Contact form links :
    - Links located in the introduction section on a main page and in the new cocktails section are both working properly.

- Activities:
    - "Divider" photo is successfully being removed on mobile devices. 

- Videos :
    - Youtube video on a menu page is working and linked properly.
    - User can control a video and it won't auto start. 

- Background images :
    - Menu and contact form background photos are linked correctly.
    - Images are successfully scaling on mobile devices. 

- Grid system(Bootstrap) :
    - Grid system is working as intended successfully changing amount of collumns on smaller devices making website fully responsive. 

- Contact form :
    - The form is working as intended.
    - The form is successfully redirecting the user to the "thank you" page.
    - Submit button is working correctly. 
    - The form is looking good on smaller devices.

- Thank you page :
    - The page is successfully appearing to the user after filling up the form.
    - The button taking the user back to the home page is working.

#### Devices used during testing:

- Desktop Computer
- Iphone 13
- Lenovo Tab M10 Plus

### Chrome Dev Tools

Chrome dev tools was used throughout the development of the project to test responsiveness. 
Responsiveness was tested using Dev Tools to emulate the following devices :

- Iphone SE
- Iphone XR
- Iphone 12 Pro
- Iphone 14 Pro Max
- Pixel 7
- Samsung Galaxy S8+
- Samsung Galaxy S20 Ultra
- iPad Mini
- iPad Air
- iPad Pro
- Surface Pro 7
- Surface Duo
- Galaxy Fold
- Samsung Galaxy A51/71
- Nest Hub
- Nest Hub Max

### Browser Testing

During development, webpage was mainly tested on Google Chrome. 
However, during testing process below browsers have been used :

- Google Chrome
- Microsoft Edge
- Mozilla Firefox
- Opera
- Safari

### Validation

[HTML validator](https://validator.w3.org/)

- 0 errors
- 0 warnings
- 18 info messages which are cased by CodeAnywhere's built-in code beautifier. CodeAnywhere is adding closing tag to the self-closing tags and causing this info messages.

![HTML validator results](https://github.com/PatrycjaBlaszkowska/project-WizardsTower/blob/main/docs/testing/HTML-validator.PNG)

[CSS validator](https://jigsaw.w3.org/css-validator/)

- 0 errors
- 0 warnings
- 0 info messages

![CSS validator results](https://github.com/PatrycjaBlaszkowska/project-WizardsTower/blob/main/docs/testing/CSS-validator.PNG)

### Bugs and Fixes

- Navbar wasn't "pushing" content down despite margin and padding :
    - Resolved by adding Bootstrap's "fixed-top" class to the navbar's tag. 

- Activities section was not working properly on smaller devices when created with div's and positioned with a float attribute. 
  Float caused this section to overlapp content under it on a mobile device :
    - Decided to use Bootstrap's grid system instead. 

### Un-resolved Bugs

- HTML validator showing 18 info messages due to the built-in code beautifier in CodeAnywhere :
    - Asked other students on Slack.
    - Looked for a similar issue on a stack overflow.

## Deployment 

The master branch of this repository is the most current version and has been used for the deployed version of the site.
The Code Institiue student template was used to create this project.

[Code Institute Template for CodeAnywhere](https://github.com/Code-Institute-Org/ci-full-template)

1. Click **Use This Template** button.
2. Give your repository a name, and description.
3. Open [CodeAnywhere EDI](https://app.codeanywhere.com/) and log into your account.
4. Click **New Workspace** button.
5. Create a workspace from your project repository by creating a clone.

### Creating a clone

1. From the repository, click **Code**.
2. In the **Clone >> HTTPS** section, copy the clone URL for the repository.
3. Paste a link into the designated area on the CodeAnywhere. 

### Forking

1. From the repository, click **Fork**.
2. Give your repository a name.
3. Click **Create fork**.

## Credits

### Images :

- Pinterest
- Pixabay
- Unsplash
- Wallpapercave

[Hero image - desktop](https://unsplash.com/photos/person-holding-wand-on-top-of-bowl-3n7DdlkMfEg)
[Hero image - mobile](https://www.pinterest.jp/pin/132785888997843042/)
[Wizard's tower activities photo](https://wallpapercave.com/magic-forest-wallpapers)
[Menu background photo](https://pixabay.com/photos/candles-pumpkins-witch-skull-1868640/)
[Contact us page photo](https://pixabay.com/photos/candle-lamp-room-inside-furniture-3272201/)

### Videos :

- Youtube

[New cocktails video on menu page](https://www.youtube.com/watch?v=kiWn5G9ODOw&ab_channel=Specs1962)

### Code :

- [Hover.css](https://ianlunn.github.io/Hover/) :
    - Used for hovering effects.

- [Code Institute, Love running project](https://github.com/Code-Institute-Solutions/Love-Running-Solutions) :
    - Inspiration for a contact page/form.

- [Bootstrap version 4.6](https://getbootstrap.com/docs/4.6/getting-started/introduction/) :
    - Used for navigation bar, grid system, contact form.

- [Font Awesome](https://fontawesome.com/) :
    - Used for all icons across the website.

### Cocktails and mocktails specs / recipes

- [Cocktails](https://dinewithdrinks.com/best-magic-themed-cocktails?fbclid=IwAR2cZ37X4-JpNm5xbG__DC-Kgg0GowdF6LWfBy797xNa8e2M_6toNz7MeiI)
- [Mocktails](https://advancedmixology.com/blogs/art-of-mixology/halloween-mocktail-recipes?utm_content=cmp-true&fbclid=IwAR08RSi3WEdzah0ay4dHni9KvTIi5GvgeGQA_xPr1ywQSusQgO0UGSqtTZA)

I mixed some recipes from both sites to create few "unique" potions. 


## Thank you to everyone who read this documentation! 
