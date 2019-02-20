# The Sixth Row 

This project is to showcase my own former band. We have a lot of unreleased music, photos and videos that have never been featured in a specifically designed
website. 

The project will be an easily usable four-page website that will enable the user to listen to music, watch videos, read info, view photos and contact the 
band, as well as see when upcoming shows are taking place. Also, links will be provided to other social media sites, such as YouTube, Facebook and Soundcloud.  

[https://robsimons1.github.io/the_sixth_row/]

## UX

In order to make the user experience as easy and enjoyable as possible I opted for a straight forward layout design using colours that are included in 
The Sixth Row logo, mainly red, black and green. The original concept for the homepage can be seen in the *supporting_docs folder* under *homepage_wireframe* 
that I created in Balsamiq. Since the original idea for the homepage there have been a few modifications.

The website is aimed at existing fans of the band, as well as potential new fans and anyone interested in having us play at a gig, wedding, party etc. 
The individual will be able to listen to our music, watch videos, see photos and contact us via an online form and also, see if there are any upcoming 
gigs / shows

I believe that a website specifically for our band is the best way to showcase our back catalogue of music, videos and photos and the four pages utilised contain the correct amount of information required by the user. 
The website allows the user to perform actions such as:

*	Easily play songs in audio format on the homepage audio players under the tile ‘Music’. These audio clips have their own controls.

*	Read information about the band in the homepage biography / history section titles ‘Audio Smackdown’ and also in snippets of text that accompany the 
    videos.
    
*	Easily play songs and shows in video format on the homepage and page titled ‘Shows / Videos. These videos have their own sets of controls and can be 
    full screened, dependent upon the user’s requirements.
    
*	View photos of the band and members in the header and also in the ‘Gigs / Members’ page. 

*	See upcoming gigs in the form of a flyer or potentially lit on the ‘Gigs / Members’ page.

*	Access various social media sites relating to the band (e.g. Facebook, YouTube, Soundcloud) via easily recognisable links in the footer section that is 
    viewable at the base of every page.
    
*	Easily contact the band with an online contact form that can be used to request gigs or general info.  This can be done via the ‘Contact’ page, where an easily managed form can be completed. There is also a link to the contact page via a button titled ‘contact’ in the footer.

## Features

### Existing Features

**Home Logo –** This is the bands online logo that is positioned in the top left corner of the home page, but is designed not display on devices smaller than          an ipad (min-width:320px) and (max-width:640px), in order to allow the Nav Bar to be at the top. It is also a link back to the home page. 
            
**Nav Bar –** Four easily usable page titles that pulse when hovered over. Images as well as text are used to describe each buttons function.

**Header Image –** Displays a photo of the band playing live.

**Audio Smackdown –** a brief biography / history of the band.

**Home Screen Video –** Allows user to watch video embedded on the home screen.

**Music Audio Player(s) –** Allows user to easily access recordings from the band.

**Social Media Links –** Links to the bands different social media pages are displayed in the footer. These are easily recognisable from their individual logos.

**Contact Button –** Explains availability and takes user straight to contact page.

**The Sixth Row Label –** Bottom right hand corner of footer, also is a link to homepage.

**Shows / Videos Page Videos –** Displays one song from the band and a full thirty eight minute show. 

**Upcoming Gigs –** This section shows the bands next live gig in the form of a flyer showing relevant information.

**Band Member Names and Photos –** Allows the user to see pictures of each band member and what they do in the band.

**Contact Form –** This is where the user can contact the band in order to book gigs ask questions. The form is simple and asks for three basic pieces of 
               information. 

### Features left to implement

**More pages -** Currently feels like there are items that could be separated (e.g. Gigs/Members)

**Working Social Media Links -** Currently Social Media links do not link to any pages.

**Working Contact Form -** This will eventually be recieved correctly and able to respond to. 

**Page hosted correctly** The page will eventually be hosted as a stand alone page, for example [www.TheSixthRow.com].

## Technologies Used
The languages, frameworks, libraries and other tools utilised for building this website are:

*	**HTML 5 -** The website uses HTML5 as a fundamental basis for building the website.

*	**CSS3 -** The website uses CSS3 for styling of all elements within the website. It is linked from the each page to the *style.css* file and is used for all content, including such as layout of color and background, images, video, audio etc.

*	**Bootstrap 3.7.6. -** The open-source Bootstrap framework has been used to implement some basic templates for forms, buttons and navigation. Bootstrap is also utilised to accommodate the responsive and mobile first design of the web page. [https://getbootstrap.com/]

*	**Cloud9 AWS (Amazon) -** Cloud9, a cloud-based integrated development environment (IDE) that has been used to write, run, and debug the code used for the website. [https://c9.io/rsimons]

*	**GitHub -** GitHub has been used for version control of the code by using Git functions in the control panel. Github was utilised frequently during the development of the website.  [https://github.com/]

*	**Font Awesome -** The website uses Font Awesome for certain icons (e.g. icons in the Nav Bar). [https://fontawesome.com/v4.7.0/icons/]

*	**Google Fonts-** The website uses Google fonts to accentuate certain text. [https://fonts.google.com/]



## Testing

Various methods of testing have been carried out to test the code of the website. Continuous testing throughout the development has been implemented to check the quality of the code. The aim is to check the functionality of the code on different devices (mobile, tablet, desktop) with an overall perspective of responsive and mobile first design.
The site has been viewed and tested in **Firefox**, **Safari**, **Chrome** and **Explorer**. The devices used to test the site are **iPhone 5/SE**, **Samsung Galaxy**, 
**iPad**, **iPad Pro** **iPhone X**, **iPhone 6/7/8**, **Hudle** and **Samsung laptop**. 

The wireframe for the Home page can be seen in the *supporting_docs folder* under *homepage_wireframe* and this was used initially to plan the site and build around. 
The opinions of numerous people were asked in the final stages of the project.

The main basic functions of the web site that required rigorous testing in different scenarios are listed below.

*	**Main Navigation** -
    * Hover mouse over navigation bar tabs **Home**; **Shows/Videos**; **Gigs/Members**; **Contact**; and ensure that they pulse.
    * Click **Home**; **Shows/Videos**; **Gigs/Members**; **Contact** tabs to ensure that they direct user to correct page.
    * Use all navigation buttons on different tablet and mobile screen size resolutions to ensure that they function correctly.

*	**Links** -
    * Hover the mouse over the **Social Media** links to ensure that they turn from green to red on different tablet and mobile screen size resolutions devices to 
      ensure that they function correctly.
    * Click *Sixth Row Logo** in Header and Footer to ensure that this redirects the user to the Homepage.
    *	Hover over **Contact** button in footer to ensure that this turns from green to red.

*	**Contact Form** -
    * Checked all three input sections of the contact form **Name**; **Email** and **How can we help?** to ensure that all fields require data in order to submit.
    * Ensure that email address must be input in correct format and error message is displayed if this is not true (e.g. must have @ symbol)
      on different tablet and mobile screen size resolutions to ensure correct functionality.
    * Ensure that button titled 'Speak to T6R' in the contact form changes from green to red when hovered over.
    
*	**Audio Files** -
    * The audio files on the **Home** page need to be tested accross numerous browsers, devices and resolutions to ensure that they look and play correctly, 
      as they are key to the to presenting the bands music on the website. 
        
*	**Video Files** -
    * The video files on the **Home** page and **Shows/Videos** page need to be tested accross numerous browsers, devices and resolutions to ensure that they look 
      and play correctly, as they are key to presenting the band on the website. 

*	**Responsive / Mobile First design** -
    * All of the **Home**; **Shows/Videos**; **Gigs/Members**; **Contact**  pages have a **Header**; **Section** and **Footer**. These needed to display correctly accross 
      all devices and screen resolutions. primarily checks are required to ensure that the website collapses in to columns in mobile view and that the information is 
      presented in a clear and legible fashion.
    * The Sixth Row Logo in the heading was removed in tablet and mobile view in order to have the Nav Bar at the top of the page on all pages. This was done to provide a 
      better user experience and clarity of design.    

## Issue List

  | Issue  |                 Description                     |       Solution                      |  
  | ------ |:-----------------------------------------------:|:-----------------------------------:|
  |   1    | Used rows for Homepage that created too much free space when viewing on resposive devices | Amended rows to columns |
  |   2    | Audio players pushing margins out of sync | Amended max-width to 100% |
  |   3    | Logo took up too much space in responsive views | Changed display to none in media query below tablet resolution |
  |   4    | Videos too large in resolutions below tablet view | Added media query to amend video sizes below tablet views |
  |   5    | Images and videos not linking correctly | Utilised relative formatting for links |
  |   6    | 'Audioweb' font not legible in Safari browser | Changed font to 'Kanit' |
  |   7    | Bootstrap 'col-xs-10 col-sm-10' not allowing Home video to play | Removed from home video Div |
  |   8    | Too much space in mobile first margins | Decreased margin sizes |
  |   9    | needed to validate HTML for debugging purposes | Utilised WC3 Markup Validation Service |
  
## Deployment

The website is designed in the AWS Cloud9 environment and regularly commited and to GitHub after each crucial peice of coding. Using this method as a sanity check 
for the development enabled me to restore the site back to previous stages when it functioned correctly or easily find lost pieces of code. 

The Git process utilised is as follows:

  1. Local Cloud9 environment used to build the site 
  2. Commited files to the staging area 
  3. Pushed files to the working environment, which then updates the repository and is also viewable as a link [https://robsimons1.github.io/the_sixth_row/] for testing on other devices and screen resolutions

## Credits 

### Content

This README file is based on the Code Institute template.

### Media 

All media files used were created and developed by The Sixth Row for the design of the project.

### Acknowledgments

Thank you to my fellow band members of The Sith Row for making this an enjoyable project that I felt passionately about. I would like to thank Anthony Ngene (https://github.com/tonymontaro) for his invaluable feedback, as supervisor for this project. 
