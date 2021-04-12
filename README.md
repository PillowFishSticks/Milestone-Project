<div align="center">
    <img src="" href="#" target="_blank" rel="noopener" alt="Home page"/>
</div>


[The Resume Website](website) was designed, built and deployed by Mark Percy as his first project for the Code Institute Full Stack Web Development diploma. The  purpose of the resume website is to showcase experience and projects to potential employers, including education, experience, and projects completed. 

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
    - [Databases](#databases)
    - [Libraries](#libraries)
    - [Languages](#languages)

5. [Testing](#testing)
    - See separate [TESTING.md](TESTING.md) file.

6. [Deployment](#deployment)
    - [How to run this project locally](#how-to-run-this-project-locally)
    - [Heroku Deployment](#heroku-deployment)

7. [Credits](#credits)
    - [Content](#content)
    - [Images](#images)
    - [Code](#code)
    - [Acknowledgements](#acknowledgements)

8. [Contact](#contact)

----

# UX

## Goals

### Visitor Goals

The target audience for the resume website is:
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

The Goals of the Reesume Website are:
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

The resume website was made to be serious, but with a fun side, with the emphasis on highlighting my education, experience, and previous projects. The following desiign choices were made bearing this in mind:

### Fonts
- The primary font 'exo' was chosen to be the main text of this site as it is simple, and looks professional. 

- The secondary font 'Roboto' was chosen for the main headings as it is very popular, looks professional, and styles well in both lower and uppercase.

### Icons
- Very few icons were used, ass to avoid overcrowding. 
- The **envelope** icon was placed next to the site owners email address to make it stand out, and to make it's purpose clear when doing a quick glance.
- The **phone** icon was placed next to the site owners phone number to make it standout, and to make it's purpose clear when doing a quick glance. 
- Yellow **cheese icons** are used as pointers between breadcrumb links on pages that have worked their way deeper into the hierarchical structure of the website 
- **Star icons** are used in the testimonials section of the home page, to emphasize the high level of reviews the shop already has on Etsy.
- The **Facebook logo** icon, **Instagram logo** icon, **LinkedIn logo** icon, and **GitHub logo**icon are included in the footer to lead visitors to the site owners social meedia accounts.

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
- The navbar features on every page except the checkout pages. It was deliberately not included on those pages as that is the standard for online shops, to remove distractions and links that would take the user away from their cart once they decide to start the checkout process.

- The navigation bar features The House of Mouse logo on the far left, which links to the home page of the site.

- **In desktop view** on the left side of the navbar is a list of the key website pages: Home, Shop, About and FAQs. The Shop link is a dropdown menu which lists out the sections of shop products.

- On the right side of the navbar are the links to contact page, search page and shopping cart.

- A user who is currently logged out will also see options to register or log into the website.

- A user who is logged in will see options to view their account page or log out.

- The shopping cart icon is located to the far right of the navigation bar. Once a user has added at least one item to their cart a blue circle will appear with the total number of items in their cart displayed within it. If the total number is 10 or more then the circle will display "9+" to save from extending the text over the size of the blue circle indicator. 

    - The indicator was chosen to mimic notification icons users are used to seeing in online shops and social media etc.

    - The blue color was chosen because it contrasts well with the rest of the sites colors and draws the eye.

    - The shopping cart counter works even for a user who is not logged in. This is because all the information about which products the user has added to their cart is stored in their session data. This makes it possible for a new user to add things to their cart before being asked to log in or register. 

- When a user is on a page listed in the navbar the text for that page is highlighted with a deeper color, and `<span class="sr-only">(current)</span>` is added to the relevant html for screen readers to tell which page the user is on.


<div align="center">
    <img src="https://i.ibb.co/c2mT77b/navbar-mobile.png" alt="The House of Mouse Navbar on mobile devices" aria-label="The House of Mouse Navbar on mobile devices" />
</div>

- **In tablet and mobile view** the logo remains in the left side of the navigation bar, where users would expect it to be. 
- The shopping cart icon is displayed in the middle of the navigation bar, and the burger icon to display the full navigation menu is on the far left, again because that is where a user would expect to find it.

#### Footer

![Footer](https://i.ibb.co/n8k7swY/footer.png)

- The footer features on every page except the cart and checkout pages. It was deliberately not included on those pages as that is the standard for online shops, to remove distractions and links that would take the user away from their cart once they decide to start the checkout process.

- The footer features The House of Mouse tagline at the top, designed to speak to those most likely to enjoy the products for sale. Under this is a link to The House of Mouse newsletter signup form, hosted by Mailchimp.

- Underneath the newsletter signup button is a list of the shops categories, making it easy for the user to find a section they are most interested in. On the right side a list of the most commonly used links. 

- The footer background of grey was chosen to provide some contrast and obvious separation between the footer and the rest of the content on the page. The Headings are displayed in pink with the links all in white. When the user hovers over a link it gently turns pink.

- The footer features the copyright information for The House of Mouse, with the 2nd year date automatically updated with Javascript as each new year begins.

- The footer also includes a link to The House of Mouse active social media channel on Facebook. If/When The House of Mouse reactivates their other social medial channels on twitter/instagram/pinterest then these can be added to the icons in the footer.

### Home Page

**Hero slider/carousel**
- The home page hero slider/carousel features 3 slides of promotional images from The House of Mouse. There are 4 images in total used as the last slides image is different for mobile and desktop. The reason for this was that the image gets too cropped when in a wide screen, while looks much better when the dimensions are taller than wide. So this image was saved for mobile screens, and another chosen for wider screens. 

**Introduction and brief pitch**
- Below the hero slider is a concise introduction to The House of Mouse, what it is, who created it and what their mission is.
- A "learn more" button leads a user to the About page where they can read the story behind The House of Mouse. 
- Icons are used to deliver information on the quality and scope of the shop quickly. The information here is deliberately short and to the point, as this page is most likely where a brand new customer would land first and it is important to use this space effectively to help convert sales.

**Shop categories**

![Shop categories](https://i.ibb.co/rkRpHq8/sections.png)

- Below the site introduction are a selection of the shop categories, displayed with beautiful product photographs and clear headings. The user can click any of these images to be taken to the relevant sections of the shop.
- On desktop view these sections are displayed with 2 larger images and 4 smaller ones, to give some visual contrast. On smaller screens each section image is the same size, so save space.

**Testimonials carousel**

![Testimonials carousel](https://i.ibb.co/3fLPkQy/reviews.png)

- A carousel of 5 reviews from The House of Mouse customers on Etsy. Each displays a 5 star rating and the review written by a customer. At the bottom of the carousel is a "read more" button that links to The House of Mouse Etsy shop reviews section, where the user can read more of the reviews for this shop.

**Featured listings**

![Featured listings](https://i.ibb.co/TLZS3Gw/featured.png)

- At the bottom of the home page 4-6 products are selected from the products database from those with `featured = True` in their properties. 4 products are displayed on desktop, and 6 on mobile and tablet size screens.
- A "browse more" button is placed underneath the featured listing inviting the user to go to the shop page.


### Resume Page

**Category buttons**
- The main shop page features a collection of buttons leading to each section of the shop. These buttons are not visible on mobile view to save space, as they can also be accessed from the navbar.

**Sort results**
- The main shop page includes the option to sort its results by "featured", "price: high to low" and "price: low to high".

**Products list**
- Products in the shop are displayed as thumbnail images with their title and price displayed underneath each photograph.
- Shop results are paginated by 12 items at a time. This number was chosen because 12 can be evenly divided by 3 and 4 making is possible to display results 4 to a row on desktop, 3 to a row on tablet and 1 on top of each other on mobile screens.
- Each product in the list has a link to it;s respective product listing with more photographs and information.

**Pagination** 
- Pagination buttons are provided depending on the number of results returned from the database with options for "First", "previous", "next" and "last" as well as the page number the user is currently on.

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

To deploy the resume website to GitHub Pages, take the following steps:

1. Create a `requirements.txt` file using the terminal command `pip freeze > requirements.txt`.

2. Create a `Procfile` with the terminal command `echo web: python app.py > Procfile`.

12. Once instances of these items exist in your database your heroku site will run as expected.

# Credits

### Images
- Project images were taken from Code Institutes mini projects that we had to complete.
- The profile image was taken from my personal collection of photos. 

## Code

- The following websites helped me undestand and create my website, by viewing examples and explanatons.
    - [Python Django Web Framework by freeCodeCamp.org]()
    - [Python Django Tutorial by Corey Schafer]()

- The README file template was taken from Anna Greave's 'The House of Mouse' project. 
    - [The House of Mouse by Anna Greaves ]()

## Acknowledgements

 - Special thanks to my mentor [Name](githubprofile) for his time, and guidance with this project. 
 - Code Institute tutors for helping support and guide me in the right direction with my code.

Thanks! Mark 



