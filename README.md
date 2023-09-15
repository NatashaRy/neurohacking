# **Site Title**
## **Site Overview**
NeuroNova is an initiative in the realm of cognitive enhancement. We want to provide individuals with knowleadge, tools and techniques to unlock their brain's full potential. Our site is intended to target individuals who are keen on personal growth and cognitive advancement, but also be appealing to professionals aswell as students, and anyone curious about the vast capabilities of the human mind. 
​
![Am I responsive screenshot](imagelocation so maybe docs/image.jpg)
​
## Table of contents:
1. [**Site Overview**](#site-overview)
1. [**Planning stage**](#planning-stage)
    * [***Target Audiences***](#target-audiences)
    * [***User Stories***](#user-stories)
    * [***Site Aims***](#site-aims)
    * [***Wireframes***](#wireframes)
    * [***Color Scheme***](#color-scheme)
    * [***Typography**](#typography)
1. [**Current Features Common to all pages**](#current-features-common-to-all-pages)
    * [***Header Element:***](#header-element)
    * [***The rest of your features***](#features)
    * [**Footer**](#footer)
1. [**Future-Enhancements**](#future-enhancements)
1. [**Testing Phase**](#testing-phase)
1. [**Deployment**](#deployment)
1. [**Tech**](#tech)
1. [**Credits**](#credits)
    * [**Honorable mentions**](#honorable-mentions)
    * [**General reference**](#general-reference)
    * [**Content**](#content)
    * [**Media**](#media)
​
## **Planning stage**
### **Target Audiences:**
​
* Users interested in understand and learn more about neurohacking and its benefits.
* Users interested in enhancing their cognitive abilities.
* Users interested in personal growth, self-awareness, and achieving a deeper understanding of their mind.
* Users interested leveraging cutting-edge research and techniques for mental well-being and optimization.
​
### **User Stories:**
​
* As a user, I want to see what the sites topic is.
* As a user, I want to be able to navigate on the site.
* As a user, I want to learn more about and understand what what neurohacking is.
* As a user, I want to be able to contact the site.
​
### **Site Aims:**
​
This is optional but offers the insight into what the aim of the project are
​
* To inform the user on opening times
* To inform the user about what we offer when they are here
* To offer the user an oppertunity to get in contact
​
​
### **Wireframes:**
​
![desktop-wireframes](docs\images\desktop.png) ![tablet-wireframes](docs\images\tablet.png) ![mobile-wireframes](docs\images\mobile.png)
​
### **Color Scheme:**
​![color-scheme](docs\images\ui-elements-color-palette.png)
We wanted ​the site to feel futurustic and make the user feel like like their encounting with something innovative and cool. Since we focus a lot on personal development and self-improvement our chosen colors which represent that. 

Our main color is green (#00C853), it use to be associated with something fresh, innovation and growth. 
We also have to kinds of blue accent colors, one lighter shade (#00E5FF) and one dark shade (#1A237E). Blue colors make people feel trust and brings calm. The lighter one is also a fresh, innovative and clear color which is very visible, because of that we have chosen not to use it too frequently, only for details, so the user think the site is a pain to visit. The darker shade symbolises depth and are a bit mystorius, which also suites NeuroNova good because neurohacking is a quite unexplored area for most people. 
We have also a light (#F5F5F5) and a dark shade (F212121) to make it easier to match colors in back- and forground in a harmonic and plesant way. 

We decided to change the use for the colors and focus on a darker background and lighter colors for body text and headings, because we thoguht it would align more with the sites purpose and feeling and thought we want our users to have.

​
## **Typography**
​​![Typography](docs\images\ui-elements-typography.png)
* Throughout the page, there are two fonts used:
  * Proxima Nova - Font-weight bold - used for headings, navigation and buttons. Buttons and navigation have uppercase applied as a text transform to make them pop compared to other text.
  * Open Sans - For rest of the element, such as body text and our form. 
​
* Proxima Nova and Open Sans are a great font pair, proxima as a thougher, bold font which open sans smooth can work together with without being to much.
* All fonts were sourced from Adobe fonts through a link to the webtyp-kit we have created.
​
## **Current Features Common to all pages**
​
#### *Navigation Bar:*
This is an example of the features section, your going to talk about each section of the page and what it offers for the navbar for example
​
* The user is given links to each section of the page
* Each option is presented in a way that is always obvious and reable
* on smaller screens a hamburger menu is provided to ensure mobile users have an optimal experience
​
#### *features
​
* This is where you will place all of your features think about each section of the page include a screenshot and a few bullet points on how it's presented and why
​
## **Future-Enhancements**
​
A webpage is a living beast it's going to evolve past the initial stages of release generally, it's always good to discuss where you this the page may go in the future
​
* At the time of making this page i didn't have the understanding to actual send e-mails from the contact form so intergration with email.js to send e-mails would improve the users experience
​
* Due to the subject matter, we have discussed the idea of including a small JS game to engage the user
​
## **Testing Phase**
​
This is the hardest bit of the readme, when we have completed a page we need to discuss testing.
​
Here is a good idea to talk about how and why you have tested with certain tools and validators so here a list of things to talk through
​
* Responsiveness - How do you test this, dev tools? checking on multiple devices?
​
* Functionality - Each feature needs to be tested before something is complete, talk about the process, click each link check each image, does form validation work, if your using javascript or anything else, does it always behave as the user expects
​
* Validators - Here include images from w3c html validator and css jigsaw (jshint for js and pep8 for python) and the results that came from it

## **Manual testing:**
NeuroNova has been tested for resposivness in the following ways:

**Resposiveness**
We have tested this to see the that the user will get the same experience visiting our website, no matter what device they choose to use. 

* Chrome dev tools - We have used Chrome Dev Tools to check the responsiveness of the website. 

We have tested the site with Dev Tools in the following ways:
1. Live simulation of the site thought VS Code.
2. Published page on GitHub. 

Ways we have used Dev Tools:
1. Narrowed the screen when opening Dev Tools.
2. Checked different devices and dimensions.

## **Functionality:**

## **Validators:**
​
​
## **Bugs**
​
We always have bugs in development, a few bullet points here to talk about bugs you found and how you fixed them, in later projects this will be more detailed

**Responsive navigation menu**
* Issue - Mobile menu is only working in Chrome developer tools. It does not work on mobile devices (Samsung Galaxy s22 Ultra) at all.
* Cause - What causes the problem is uncertain at this momemnt. We've tried different kinds of menus on mobile but get the same issue. I have not found a resolution for this bug yet.
* Resolution - Due to limited time, we chose to make a temporary solution and add an extra section for the menu in smaller units. We know that it is not an optimal solution, but it contributes to the site's functionality and is kept within the framework of the deadline.
​
**Overflow on smaller screens**
* Issue - On smaller screens it was possibke to scroll horizontal. We could see this during our manual testing. 
* Cause - The FAQs styling were not optimized enough with made it go out of the screen. 
* Resolution - Changed width to auto for screens 720px or below, which solve the problem.  

**Non-visible images**
* Issue - During development and after deployment we noticed that images in the directory would not apperear on the website.
* Cause - The path to some of the images was not relative, make them non-visable on Github pages. 
* Resolution - Changing the path to the source and the images got visable again.   
​
***
## **Deployment**
I deployed the page on GitHub pages via the following procedure: -
​
1. From the project's [repository](https://github.com/NatashaRy/neurohacking), go to the **Settings** tab.
2. From the left-hand menu, select the **Pages** tab.
3. Under the **Source** section, select the **Main** branch from the drop-down menu and click **Save**.
4. A message will be displayed to indicate a successful deployment to GitHub pages and provide the live link.
​
You  can find the live site via the following URL - [live webpage](https://natashary.github.io/neurohacking/)
***
​
## **Tech**
​
The technologies used in this project are:
​
- HTML
- CSS
​
## **Credits**
### **Honorable mentions**
​
It's always nice to mention those that helped you get there, if people gave you support on slack or the local cat scared you into completing give them a mention!
​
### **Content:**
​
If you took any code from online source and by this i mean copy paste with zero changes mention it here!
- Icons in footer was taken from [Fontawesome](https://fontawesome.com/)
- Used this guide as inspiration for FAQ: [Stechies.com](https://www.stechies.com/create-accordion-html-without-javascript/)
- Most of the texts are written by or modified by Chat GPT4, based on my promts [Chat GPT](https://chat.openai.com/)
  
### **Media:**
- Hero background image:: [Canva PRO](https://www.canva.com/photos/MAEEzSWsTXg-artificial-intelligence-technology/)
- Image on about-section: [Stockvault](https://www.stockvault.net/photo/264052/technology-disruption-the-rise-of-artificial-intelligence)
- Background image on benefits- and FAQ-section: [Canva PRO](https://www.canva.com/photos/MAEEzSWsTXg-artificial-intelligence-technology/)
- Video on How it works-section is created with [Chat GPT4 + Visla-plugin](https://chat.openai.com/)