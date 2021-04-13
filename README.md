[The Resume Website](website) was designed, built and deployed by Mark Percy as his first project for the Code Institute Full Stack Web Development diploma. The purpose of the resume website is to showcase experience and projects to potential employers, including education, work experience, and projects completed. 

## Table of Contents
1. [UX](#ux)
    - [Goals](#goals)
        - [Visitor Goals](#visitor-goals)
        - [Site Owner Goals](#site-owner-goals)
    - [User Stories](#user-stories)
    - [Design Choices](#design-choices)
    - [Wireframes](#wireframes)

2. [Features](#features)
    - [Existing Features](#existing-features)
        - [Home Page](#home-page)
        - [Resume Page](#resume-page)
        - [Projects Page](#projects-page)
        - [Contact Page](#contact-page)
    - [Features for Future Releases](#features-for-future-releases)


3. [Technologies Used](#technologies-used)
    - [Tools](#tools)
    - [Libraries](#libraries)
    - [Languages](#languages)

5. [Testing](#testing)
    - See separate [TESTING.md](TESTING.md) file.

6. [Deployment](#deployment)
 
7. [Credits](#credits)
    - [Images](#images)
    - [Code](#code)
    - [Acknowledgements](#acknowledgements)

----

# UX

## Goals

### Visitor Goals

The target audience for the resume website are:
- People who are looking to employ a fullstack developer.
- Recruitment agencies recruiting potential candidates.
- Potential employers doing further research into their employee.
- People wanting to view projects and experiece for potential business.
- Potential clients looking for a freelance developer.

User goals are:
- To see educational qualifications of a potential employee. 
- To see work experience and knowledge of the profession.
- To view previous project coompleted.
- To recruit or employ the candidate, if they meet all the criteria.

### Site Owner Goals

The Goals of the resume website are:
- To display educational qualifications. 
- To share work experience and knowledge.
- To showcase projects to potential employers.
- To attract potential clients for business.

## User Stories

As a visitor to Mark Percy's resume website I expect/want/need:

1. To be able to easily find the information I am looking for, the layout needs to make sense so that I am not put off. 

1. The site to be laid out in a way that is easy to navigate, so that I can find what I need. 

1. The site to be responsive and navigable for various device sizes; desktop, tablet, and phone. For the content to look good on all of the devices.

1. To learn more about the site owner.

1. To be able to view the site owners educational background, to ensure they are qualified for the job.

1. To be able to view the site owners previous job experience. 

1. To be able to download the site owners cv, to share and keep for future use. 

1. To be able to see previous projects completed, as well as read a short description about the project.

1. To be able to connect to the site owners social media accounts. 

1. To be able to easily get in contact with the site owner via a contact form.

## Design Choices

The resume website was made to display education, work experience, and projects, with a fun side. With emphasis on highlighting my education, experience, and previous projects. The following design choices were made bearing this in mind:

### Fonts
- The primary font 'exo' was chosen to be the main text of this site as it is simple, and looks professional. 

- The secondary font 'Roboto' was chosen for the main headings as it is very popular, looks professional, and styles well in both lower and uppercase.

### Icons
- Very few icons were used, as to avoid overcrowding. 
- The **envelope** icon was placed next to the site owners email address to make it stand out, and to make it's purpose clear when doing a quick glance.
- The **phone** icon was placed next to the site owners phone number to make it standout, and to make it's purpose clear when doing a quick glance. 
- The **Facebook logo** icon, **Instagram logo** icon, **LinkedIn logo** icon, and **GitHub logo** icon are included in the footer to lead visitors to the site owners social meedia accounts.

### Colours
- bright pink: #FF1493
- purple: #FF00FF
- green: #32CD32
- bright green:#00FF00
- blue: #00BFFF
- bright blue: #40CCFF
- white: #f4f4f4

- The bright contrasting colors were chosen for this website because they standout on the dark background, which helps highlight important information. The bright colors also add an element of fun to the website. 

## Wireframes

These wireframes were created using [Balsamiq](https://balsamiq.com/) during the design and planning process for this project. 

- [Home]()
- [About]()
- [FAQs]()
- [Account]()
- [Shop/Search Results]()
- [Catagories]()
- [Listing]()
- [Cart]()
- [Checkout - Info]()
- [Checkout - Shipping]()
- [Checkout - Payment]()
- [Checkout - Confirmed]()

# Features
 
## Existing Features

### Elements on every page

#### Navbar
- The navbar features on every page. 

- The navigation bar features the site owner name 'Mark Percy'on the far left, and website pages on the far right which include Home, Resume, Projects, and Contact. 

- **In desktop view** on the left side of the navbar is the name of the site owner 'Mark Percy'

- On the right side of the navbar are the links to Home page, Resume page, Projects page, and Contact page.

- **In tablet and mobile view** the site owners name remains on the left side of the navigation bar, where users would expect it to be. 
- The burger icon which displays the full navigation menu is on the far right.

#### Footer

- The footer features on every page. 

- The footer features the site owners email address, phone number, and links to social media accounts. 

- The footer features links to the site owners social media accounts for Facebook, Instagram, LinkeedIn, and GitHub. 

- The content is displayed in white, when the user hovers over a link, the text turns black and the background turns white.

### Home Page 

![Home page](/img/resume-website/home.png)

**Introdcution**
- Below the navbar is a circular profile picture and next to that is a description of the site owner. 
- Below the description are threee buttons 'My Skills', 'My Work', and 'My Contact'.
- 'My Skills' take you to the Resume page. 
- 'My Work' take you to the Projects page.
- 'My Contact' takes you to the Contact page. 


**Three reasons to hire**
- Below the three buttons aree three blocks containing 'Skills', 'Best Practice', and 'Experience'. 
- 'Skills' includes the diffrent languages the site owner is proficient in. 
- 'Best practice' includes coding best practices by the site owner.
- 'Experience' provides a very brief summary of the site owners work experience. 

### Resume Page

**My languages**
- This section includeslanguages and frameworks that the site owner is proficient in, including HTML/CSS, Java/jQuery/ Python/Django. 

**Education**
- This section gives the educational background of the sitte owner. 
- It includes three different insertions of different content studied at different universities. 
- All iinformation is displayed in a column alongside experience. 

**Experience**
- This section displays the site owners work experience. 

### Project Page
- The category pages are built from the same template as the main shop page and displays the same buttons and sorting options.
- Pagination is not currently available for shop categories, as there is an unsolved bug with trying to then sort these results. As the number of products in a single category is never very large I opted to leave fixing this issue for a future release.

### Contact page
- The search page is built from the same template as the main shop page and shop categories pages. With the one addition of the search bar where users can enter a text search.
- On loading the search page there are no products displayed. Once the user has entered a text search the results are displayed below the search bar and paginated if more than 12 results are returned from the database.
- If no results for a text search are returned from the database then the text 
"There are currently no listings that match this search" provides feedback to the user.

## Features for Future Releases

1. **Password reset by email.**
    - I already looked into this, but it required changing settings in my private gmail account to less secure ones. Which is not something I am willing to do at this moment. When/if this site is deployed to it's own domain and is being used as a fully functioning online store, then I will invest in a separate gmail account specifically for it and get this feature set up.
2. **Sending an email to customer when their new order has been placed.**
    - This feature also required the gmail settings mentioned above, and is one that would be included if/when the site is properly launched.
3. **Build staff pages to view all order info needed together for easier shipping process.**
    - Giving staff the ability to view all order information in one place, rather than having to visit the Stripe dashboard or admin panel to see the orders. Functionality for this page might include:

This section will continue to grow as the site is deployed to its own domain and implemented in the real word. New issues and needs will become apparent as the site is used.

# Technologies Used

### Tools
- [Git](https://gist.github.com/derhuerst/1b15ff4652a867391f03) to handle version control.
- [GitHub](https://github.com/) to store and share all project code remotely. 
- [Balsamiq](https://balsamiq.com/) to create the wireframes for this project.

### Libraries
- [JQuery](https://jquery.com) to ensure a responsive mobile navbar.
- [Bootstrap](https://www.bootstrapcdn.com/) to simplify the structure of the website and make the website responsive easily.
- [FontAwesome](https://www.bootstrapcdn.com/fontawesome/) to provide icons for the footer.
- [Google Fonts](https://fonts.google.com/) to style the website fonts.

### Languages
- This project uses HTML, CSS, and JavaScript programming languages.

# Testing 

Testing information can be found in separate [TESTING.md](TESTING.md) file

# Deployment

## GitHub Deployment

# Credits

### Images
- Project images were taken from Code Institutes mini projects that we had to complete.
- The profile image was taken from my personal collection of photos. 

## Code

- The following websites helped me undestand and create my website, by viewing examples and explanatons.
    - [W3schools](https://www.w3schools.com/)
    - [Bootsnipp](https://bootsnipp.com/)

- The following website was used for type text 

- The README file was taken from Anna Greave's 'The House of Mouse' project to use as a template.
    - [The House of Mouse by Anna Greaves ](https://github.com/AJGreaves/thehouseofmouse)

## Acknowledgements

 - Special thanks to my mentor [Name](githubprofile) for his time, and guidance with this project. 
 - Code Institute tutors for helping support and guide me in the right direction with my code.

