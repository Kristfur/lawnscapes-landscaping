# Lawnscapes Landscaping

Lawnscapes Landscapign is a website that is designed for users how are looking for landscaping services in Wexford, Ireland. The site is targeted towards homeowners, and businesses who are in need of a range of landscaping services from lawn cutting to weeding. The site is designes with a wide range of demographics in mind, it is easy to navigate and everything is just one click away.

Click [here](https://kristfur.github.io/lawnscapes-landscaping/) to view the live site.

![Responsive design example](docs/read-me-images/responsive-website.JPG)

# Features
## Site wide
- Navigation Menu
    - Menu containes links for home, services, gallery and contact pages.
    - Allows users to easily navigate the website, and it shows what page the user is currently on
    - Menu is responsive for all screen sizes

![Navigation menu wide snipet](docs/read-me-images/nav-menu-wide.JPG)
![Navigation menu narrow snipet](docs/read-me-images/nav-menu-narrow.JPG)

- Footer
    - Footer contains contact information for Lawnscapes Landscaping and social media icons
    - The socila media icons will open a new tab when clicked, and bring the user to the social media account for Lawnscapes Landscaping.
    - Footer is present on all web pages

![Footer snipet](docs/read-me-images/footer.JPG)

- Favicon
    - Favicon has reconisable company logo
    - Allows the user to easily identify website from browser tabs

![favicon snipet](docs/read-me-images/favicon.JPG)

- 404 page
    - 404 page will show if user navigates to a broken link
    - Page tells user the link is invalid and provides link to retur to home page

![404 page snipet](docs/read-me-images/404-oops.JPG)


## Home page
 - Hero image
    - This image is the first thing the user sees when the come to the website, it shows the user what the website is about
    - The image pans from right to left on smaller screens, and zooms out on larger screens to show user the whole image and to bring life to the website
    - The image has a call-to-action block of text that the user can click to go to the services page

![Hero image snipet](docs/read-me-images/hero-snip.JPG)

- Company information blocks
    - The home page has three information blocks that give the user knowledge about the company
    - Each block of text is accompanied by a related image to add to the user experience

![About info snipet](docs/read-me-images/about-me-snip.JPG)

## Services
- Service information blocks
    - This page consists of blocks that provide information on each service that is offered
    - Each block has the service name, a related image as the background and some text describing what is included with the service
    - The text on each block is clickable and will bring the user to the contact us page

![Services block snipet](docs/read-me-images/services-block.JPG)

## Gallery
- Masonry style gallery
    - This page gives the user images of the work done by our company
    - The images are arranged in a masonry style and are responsive to the screen size

![Gallery snipet](docs/read-me-images/gallery-snip.JPG)

## Contact
- Contact Us from
    - This contact form is for the users to contact the company about getting a service, and the company can get their information to contact them back
    - The form consists of the following elements:
        - First Name (required, type=text)
        - Last Name (required, type=text)
        - Phone Number (required, type=text)
        - Email Address (required, type=email)
        - Address (required, type=text)
        - Service (required, options are listed below)
            - Lawn Cut (type=checkbox)
            - hedge Trim (type=checkbox)
            - Weeding (type=checkbox)
            - Leaf Raking (type=checkbox)
            - Waste Removal (type=checkbox)
            - Other (type=checkbox)
        - Comments (optional, type=textarea)
        - Submit and Reset buttons
    - Once all required elements are filled correctly and the user clicks submit, they will be brought to a Thank You page
    - The Thank You page provides the user with a link back to the home page, but also lets them know that they can call us now if they dont want to wait for the company to get back to them

![Contact form snipet](docs/read-me-images/contact-form.JPG)
![Thank you page](docs/read-me-images/thank-you.JPG)

## Exsisting Features
- Responsive design
- Easy and intuitive to navigate
- Contact form and thank you page
- 404 page for invalid links
- 5 services for user to choose from

## Features To Implement
- Checkboxes in contact form are automaticaly selected when user clicks on a service on services page
- Database of users info for company and alert/email system for when a user submits a contact form
- Email and phone number in footer are clickable and open an email/phone platform for user to immediately and easily contact company
- Ability for images in gallery to enlarge when clicked

# Design
## Wireframes
Home page

![Wireframe for home page - phone](docs/read-me-images/p-home.png)

![Wireframe for home page - computer](docs/read-me-images/c-home.png)

Services page

![Wireframe for services page - phone](docs/read-me-images/p-services.png)

![Wireframe for services page - computer](docs/read-me-images/c-services.png)

Gallery page

![Wireframe for gallery page - phone](docs/read-me-images/p-gallery.png)

![Wireframe for gallery page - computer](docs/read-me-images/c-gallery.png)

Contact page

![Wireframe for contact page - phone](docs/read-me-images/p-contact.png)

![Wireframe for contact page - computer](docs/read-me-images/c-contact.png)

Thank You page

![Wireframe for thank you page - phone](docs/read-me-images/p-submit.png)

![Wireframe for thank you page - computer](docs/read-me-images/c-submit.png)

404 page

![Wireframe for 404 page - phone](docs/read-me-images/p-404.png)

![Wireframe for 404 page - computer](docs/read-me-images/c-404.png)

# Technologies
- HTML
    - The structure of website was built with HTML code

- Css
    - The website was styled with a CSS file

- Gitpod
    - The website was developed using [gitpod.io](https://gitpod.io)

- GitHub
    - The source code is hosted on [GitHub](https://github.com/Kristfur/lawnscapes-landscaping) and deployed with Git Pages ([Link to live website](https://kristfur.github.io/lawnscapes-landscaping/))

- Git
    - Used for version control during the development of the website

- Font Awesome
    - Icons for the social media in footer were obtained from [https://fontawesome.com/](https://fontawesome.com/)

- Favicon.io
    - Favicon files were created by [https://favicon.io/](https://favicon.io/)

- balsamiq
    - Wireframe diagrams were created using [balsamiq](https://balsamiq.com/)

- remove.bg
    - Whitespace in logo background was removed with [https://www.remove.bg/](https://www.remove.bg/)

- iloveimg
    - Images size (width/height) was reduced with [https://www.iloveimg.com/](https://www.iloveimg.com/)

# Testing
## Responsiveness
All website pages were tested for responsiveness on screen sizes of 320px and above on Firefox, Chrome, Edge and Opera browsers.

Steps taken:
1. Open browser and go to the link [https://kristfur.github.io/lawnscapes-landscaping/](https://kristfur.github.io/lawnscapes-landscaping/)
2. Open developer tools by pressing CTRL+SHIFT+I on the keyboard
3. Toggle device toolbar and set width to 320px
4. Drag window to maximum width

Expected:
The website is responsive and all elements are on screen and not overlapping, the images are not pixelated or stretched.

Actual:
Website behaved as expected

The website was also tested on the following devices for responsiveness:
- iPhone 8 (behaved as expected)

## Accessibility
The [Wave Accessibility](https://wave.webaim.org/) tool was used for accessibility testing. 

Testing was focused on the following:
- All image elements had an alt description for a screen reader to read out
- All forms have lebels for each input for a screen reader to read out
- All links to external pages have proper aria labels
- Color contrast for text meets the minimum ratio

Multiple accessibility issues were found, but were promptly resolved.

Issue #1: Color contrast of the smaller text did not meet the minimum ratio

Fix: The text color was changed from <span style="color:#578e44">#578e44</span> to <span style="color:#41612e">#41612e</span> to meet the minimum requirement

Issue #2: All of the images on the services page lacked an alt description:

Fix: All images recieved appropiate alt descriptions