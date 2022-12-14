# Happy Bee's Cafe Website

![Mockup of site displayed on different devices](docs/mockup.png)

### [Click here to view the live web application!](https://jts272.github.io/pp1-happy-bees-cafe/index.html) 

(All links can be opened in a new tab with Middle Click or by Right Clicking and selecting 'Open link in new tab')

Return to the top of the page at any time by clicking on 'README.md' at the top left of the page.

---

Welcome to Happy Bee's Cafe!

This documentation covers the interactive front-end web application for a cafe based in Halifax, West Yorkshire. It is built entirely with HTML5 and CSS3 for educational purposes, with permission and zero compensation.

Throughout development of the project, I bore in mind my principles of CARE:

- Cohesive
- Accessible
- Responsive
- Essential

We will discover how these guiding principles formed the basis of my first web application project to create an appealing, logical and valuable product. By the end of this document, we will have covered:

- UX (User Experience) development
- Design Process
- Testing of the application throughout development, implementation and deployment stages
- Code structure, integrity and organization to maximize maintainability for the future
- Version control process
- Deployment method to a cloud-based platform (GitHub Pages)
- Problems encountered and their solutions
- Development learning opportunities and ideas for future implementations

---

## Table of Contents

- [User Experience (UX)](#user-experience-ux)
  - [User Stories](#user-stories)

- [Design Process](#design-process)
  - [User Experience Development (UXD)](#user-experience-development-uxd)
  - [Practical Elements](#practical-elements)
  - [Wireframes](#wireframes)
  - [Typography](#typography)
  - [Colour Palette](#colour-palette)
  - [Imagery](#imagery)

- [Features](#features)
  - [Homepage](#homepage)
  - [Menu Page](#menu-page)
  - [Gallery Page](#gallery-page)
  - [Order Page](#order-page)
  - [Thank You Page](#thank-you-page)
  - [404 Page](#404-page)

- [Development and Testing](#development-and-testing)
  - [Functionality Testing](#functionality-testing)
  - [User Stories Testing](#user-stories-testing)

- [Validation Testing](#validation-testing)
  - [HTML Testing](#html-wc3-markup-validation-service)
  - [CSS Testing](#css-w3c-css-validation-service-jigsaw)
  - [Accessibility Testing](#acessibility-wave-web-accessibility-evaluation-tool--browser-extension-available)
  - [Mobile-Friendly Testing](#mobile-friendly-test)
  - [Lighthouse Rating](#lighthouse-open-devtools--lighthouse)

- [Version Control and Code Maintainability](#version-control-and-code-maintainability)

- [Deployment Strategy](#deployment-strategy)

- [Bugs](#bugs)

- [Workflow Optimizations and Future Ideas](#workflow-optimizations-and-future-ideas)

- [Devices and Technologies Used](#devices-and-technologies-used)
  - [Hardware](#hardware)
  - [Software](#software)
  - [Browser Extensions](#browser-extensions)
  - [Platforms](#platforms)

- [Credits and Resources](#credits-and-resources)

- [Closing Words](#closing-words)

---

## User Experience (UX)

Happy Bee's Cafe is a friendly, family run business that offers a seated cafe experience, as well as takeaway and local delivery orders. The website aims to be a complete, up to date hub for what the business offers. Users can expect to find all pertinent information such as menus and pricing, as well as how to get in touch and follow the latest updates on social channels.

The site is built from the ground up to be fully responsive with a 'mobile-first' design philosophy. The appearance and functionality of the site was built with progressive advancement in mind. This ensures that the user has a positive emotional experience interacting with the site, regardless of their chosen device. [Google](https://developers.google.com/search/mobile-sites/mobile-first-indexing) index and rank pages based on the mobile version so this design choice gears the site to be more SEO-friendly.

The CARE principles are a core part of the development process. The application is for a business with an existing branding and client base, so the website leveraged this in its design. I decided to create a site that is **cohesive** with the interior styling of the cafe itself. This idea is further expounded in the Design Process section.

**Accessibility** should be at the core of any web application. I want the full features of the site to be useable for as many users as possible. This principle is reflected through use of properly contrasting colours and effective use of accessibility features of HTML5. Web accessibility tools have been used through design and testing to ensure compliance.

**Responsiveness** is table stakes for web design in the current era, as espoused by web designer [Ethan Marcotte](https://www.youtube.com/watch?v=4twHFfU44uE). I want to provide the user with an experience that is not compromised by their device. To this end, I have chosen a [Mobile First Design](https://www.youtube.com/watch?v=JcaX60ZscgA) (MFD) for the application. The design process will further explain my approach.

Tying the above concepts together is the focus on keeping the application **essential**. In short, what needs to be there *is* there and anything which does not aid the project goals is discarded. I have found this philosophy to be at the heart of MFD as there is less screen real-estate for overly elaborate features and designs.

### User Stories

The website exists for the benefit of the business owners, their current customers and future customers. The goals outlined below shows the purpose of the site from those perspectives:

- Client Goals:
  - For potential customers to find the cafe
  - For potential customers to place an order by telephone or form
  - To project a positive brand image to attract customers to visit
  - To keep current customers in the loop and up to date

- First Time Visitor Goals:
  - To easily find the location of the cafe
  - To see what food is on offer
  - To view the price of the food on offer
  - To see the actual cafe
  - To see that there is an order function

- Returning Visitor Goals:
  - To have the ability to place customised orders for collection
  - To have the ability to place customised orders for delivery
  - To have the most up to date information on pricing

- Frequent Visitor Goals:
  - To be able to follow the cafe's social media channels to connect further
  - To use the order form to be able to place an order for event catering

The cafe is open from morning to early afternoon. It is situated on a busy road on the outskirts of Halifax. Customers coming in on a typical day could include local school pupils, passing tradespeople or an older couple for lunch. It serves a broad range of people so the website's design and values must cater to this.

---

## Design Process

### User Experience Development (UXD)

I followed the 5 planes of UX to determine the course of the project before ever writing a line of code. The 5 planes are as follows:

- Strategy
- Scope
- Structure
- Skeleton
- Surface

### Strategy

The strategy was to keep the content relevant to those who would use it and to serve the needs of the business. I conducted a brief stakeholder meeting of sorts with the cafe owner. I learned a bit more about the business and its customers to make the copy text of the website in line with customer's expectations.

As the cafe did not have a website before, nor was there much competition in the immediate vicinity, I looked online to conduct an existing product audit. I took inspiration from [The Pottery Cafe](https://thepotterycafe.co.uk/). Although different in nature from a conventional cafe, I found the general page layout, footer format and gallery layout to be of a professional standard that I should be aiming for. The site also responded well to resizing of the browser window.

The B2C format best describes the business style. Although food orders and catering are available for business, they are still customers in the conventional sense. I wanted to project a positive, welcoming image that mirrors the cafe's family friendly reputation.

### Scope

It was essential to determine the scope of the project from the beginning - what is in and what is out? The function of the site from different perspectives are detailed in the [user stories.](#user-stories) The application must meet these needs in both form and function.

The functional requirements are addressed in the [features](#features) section. The principle of essentialism helped to guide the project in the right direction, preventing scope creep from being a threat. As my first web application especially, iteration and refinement was a key part of the design process as I was learning and improving as the project progressed. I feel that the needs of the project were ultimately satisfied.

### Structure

At this level, I looked at the organization of content and features. This entailed how that pages were structured and how the user would navigate them. Interaction Design (IXD) was at the forefront of this design phase. Users have expectations for how to navigate websites on their chosen device. The key was to leverage their expectations. The flow of pages is consistent and no luck is involved in terms of user interaction. Examples of this include having the body text on the homepage 'below the fold' to encourage the user to scroll down to read more after the hero image captures their attention. For desktop users, social calls to action (CTA) change colour on mouse hover to highlight that action can be taken.

### Skeleton

This is where form is given to function. For the user, this is represented by the UI. I kept each page relevant to its stated content. I followed the [Hick-Hyman Law](https://en.wikipedia.org/wiki/Hick%27s_law) and did not want to overwhelm the user with needless choices and interactions.

Navigation is intuitive, regardless of device. The mobile site uses a navbar that contrasts nicely with the header logo and runs across the width of the screen. The desktop version uses the convention of having the header logo and navigation links on the same line, left-to-right. In both instances, the current page is highlighted to the user and the desktop site makes use of the mouse hover function to clearly show the user which link they are about to click.

The footer contains social calls to action that are represented clearly. A back to the top button is featured to keep browsing efficient and effortless.

Wireframes were drafted as a general guide for the structure of pages across devices. This expanded upon in this [section.](#wireframes)

### Surface

This is where the design culminates. Does it smell like value? By following the CARE principles and stages of design, the application forms a cohesive product that meets its needs. This comes together through the features and consistent visual style, described further below.

## Practical Elements

### Wireframes

I started by jotting on paper the features that must be included followed by some rudimentary drawings of how the pages could look on mobile and desktop. I used [Balsamiq](https://balsamiq.com/) to draft mockups digitally of how I wanted the fundamental pages of the website to be laid out.

<details>
<summary>Homepage</summary>
<img src="docs/happybeescafe.png">
</details>

<details>
<summary>Menu</summary>
<img src="docs/happybeesmenu.png">
</details>

<details>
<summary>Gallery</summary>
<img src="docs/happybeesgallery.png">
</details>

This served as template for my markup and styling, creating a clear vision for me to start with. Due to the rough nature of the sketches, iteration is to be expected. In testing the application throughout development, changes were made where it better suited the core vision.

### Typography

As I was creating a webpage for a preexisting company, I wanted it to reflect the branding already established. I chose to have a header font that matches the masthead outside the cafe:

![cafe premises logo](docs/happy-bee-logo.jpg)

I initially used various [fond finders](https://www.google.com/search?q=font+finder&ei=QydNY_68FcWw8gLziqzQBQ&ved=0ahUKEwi-6u2igOf6AhVFmFwKHXMFC1oQ4dUDCA4&uact=5&oq=font+finder&gs_lcp=Cgdnd3Mtd2l6EAMyCAgAELEDEJECMgUIABCRAjIFCAAQgAQyBQgAEIAEMgUIABCABDIFCAAQgAQyBQgAEIAEMgUIABCABDIFCAAQgAQyBQgAEIAEOgsIABCABBCxAxCDAUoECE0YAUoECEEYAEoECEYYAFAAWIoFYLYGaABwAXgAgAFoiAG6A5IBAzUuMZgBAKABAcABAQ&sclient=gws-wiz), but results were not satisfactory. Instead, I used [Google Fonts](https://fonts.google.com/). I entered the cafe's name in all caps in the preview window and selected the font that most closely matched. The drop shadow effects were later styled in CSS.

For the body text, I again relied on Google fonts. I selected a sans-serif font for easy reading across devices. I wanted a rounder, more 'friendly' font to reflect the atmosphere of the cafe. Comic Sans serves its purpose on printed media, such as the cafe's menus but is usually a cause for distraction if used on a professional website, so I avoided using this.

<details>
<summary>Paper Menu</summary>
<img src="docs/comic-menu.jpg">
</details>

### Colour Palette

I took various images of the cafe after my initial project meeting. I used a clear shot of an interior wall as both my hero image and colour palette. Although it is easy enough to select a generated 'off-the-shelf' colour palette, I wanted to create a cohesive experience from screen to real-world premises.

<details>
<summary>Cafe Interior/Hero Image</summary>
<img src="assets/images/hero-image-2000px.jpg">
</details>

In keeping with the bee branding, black and yellow is to be expected. I would naturally make use of white for contrast. By importing my hero image photo to [Coolors](https://coolors.co/), I was able to pinpoint the colours I wanted to use, down to the exact HEX or RGB code. Here are the colours I selected:

![colour palette](docs/hero-image-palette.png)

I ended up with a simple selection of colours: Black, White, Yellow, Light Brown and Dark Brown. The brown tones were taken from the different shades of wood visible in the picture. They were used effectively in the 'picture-frame' motif that is used across pages.

On pages with a dark stock image, I created a white border to help mark the divide between the main content and the footer:

<details>
<summary>Content Divider</summary>
<img src="docs/dark-bg-divider.png">
</details>

### Imagery

Imagery on the website consists of:

- A Hero Image
- Gallery Images
- Stock images for certain page backgrounds

The hero image is simple and geometric, but sets the scene and colour tone for the user. This gives them information of what to expect from the site and the seated experience quickly, without being overwhelming.

The Gallery mainly consists of image, used with permission, from the cafe's [Facebook Page](https://www.facebook.com/people/Happy-Bees-Cafe/100057339854373/). Their function is to show users that there is a broad range of high quality food available, with generous portions and a home cooked feel. Also shown are images from charity events hosted by the cafe and seasonal spreads such as Easter Eggs.

Stock imagery was used from [Pexels](https://www.pexels.com/) for page backgrounds that did not have much body content. This keeps the user interested, whilst reinforcing the cooking and bee themes. The stock images were combined with a transparent black overlay in CSS to keep contrast high and the user focussed on the relevant input sections.

---

## Features:

In determining the [scope](#scope) of the project, I planned to use 4 pages as the core of the site:

- Homepage - Sets the scene, shows important information of opening times. A brief introduction to the business and invitations to explore the rest of the site or user reviews on an external webpage.

- Menu - A fundamental feature of a cafe. Contains the full menu as presented on the cafe's own printed media. Users would expect to find the most up to date pricing here.

- Gallery - After browsing the menu, the user's appetite would be whetted to see the food on offer. I would select a broad range of different food images to showcase the standards and variety on offer.

- Order Form - Give users the option to interact with the business directly by placing an order. The form would follow a logical flow to guide users to their purchase.

In order to ensure the user is given proper feedback to confirm their actions, 2 further pages would need to be established:

- Thank You Page - Upon successful completion of the form, it is essential that the user has their input confirmed.

- 404 Page - In the event of a browsing error, this page playfully informs the user that the page cannot be found and offers to guide them safely back to the homepage.

Here we will explore the webpages in further detail. Screenshots are provided for the desktop offering:

### Homepage:

![index](docs/ss-index.png)

- Header
  - The company name and logo is featured prominently. As the user would expect, clicking this navigates back to the homepage.
- Navigation Bar
  - This includes easily identifiable links to the various pages of the site. The currently active page will have its link highlighted to confirm to the user which page they are on.
- Hero Image
  - This section intends to capture the user's attention and immediately inform them of the site's purpose. Opening times overlay an image of the seating area so that the most important information is presented immediately.
- About Us
  - Here is detailed relevant information about what the business offers. The aim is to make the user feel positive and welcomed. The potential customer should find that they will be well catered to and that this is a place they would be happy to visit.
- Footer
  - The page finishes with valuable information such as address, contact information and social links. There are calls to action for the user to connect with the business by finding the location on Google Maps or to follow the Facebook page. 
  - An easily accessible button to return to the top affords users a swift viewing experience by sending them back to the navigational links at the top of the page.

![footer](docs/ss-footer.png)

---

*The Header, Navigation Bar and Footer are consistent elements on every page.* The user would expect to know which page they are on and how to easily access the other pages of the site. The key features of their respective pages are detailed below:

---

### Menu page:

![menu](docs/ss-menu.png)

- Menus
  - Meals and pricing are displayed clearly and unambiguously.
  - The Menus are split up to reflect the paper menus available from the cafe. They are styled to resemble chalkboards hanging from the wall in CSS.
  - The menu boards are flexible items that will wrap to fit the user's screen whilst retaining the integrity of the content.

### Gallery page:

![gallery](docs/ss-gallery.png)

- Image Gallery
  - A responsive image gallery shows the user the variety and quality of the food, as well as the seating environment.
  - A 2 column layout for mobile and an interactive 4 column layout for desktop. Desktop gallery styled in CSS to resemble picture frames. On hover, the picture rises with a shadow effect to simulate taking a photo frame off the wall.

### Order page:

![form](docs/ss-form.png)

- Order Form
  - This form gives the user a way to interact in placing a custom order. Whether for a workplace lunch or a fully catered event, the customer can send their request to be prepared.
  - Responsive and retains high contrast regardless of layout.
  - Certain elements are required for the form to complete.
  - Sends user to Thank You Page upon successful completion.

<details>
<summary>Full Desktop Form</summary>
<img src="docs/ss-desktop-form.png">
</details>

<details>
<summary>Full Mobile Form</summary>
<img src="docs/ss-mobile-form.png">
</details>

### Thank You Page:

![thankyou](docs/ss-thankyou.png)

- Thank You Message
  - Informs the user that their form has successfully completed and thanks them for their input.
  - There is no back end set up in this application for the form, so the user is informed that their order cannot be fulfilled at the moment so invites them to come to the cafe instead.

### 404 Page:

![404](docs/ss-404.png)

- Guide to Homepage
  - A simple page that informs the user of the 404 error in a friendly manner.
  - A picture of a bee on a sunflower creates a positive vibe and keeps emotional reaction positive in spite of error.
  - A clear offer to navigate back to the homepage.

---

## Development and Testing

This application was coded in [GitPod](https://www.gitpod.io/), a cloud editor based on VS Code. I used the bash command line interface (CLI) to create my HTML and CSS files, as well as folder structure. Images were inserted into the images folder simply by drag and drop from Windows Explorer.

With respect to MFD, the bulk of the site was developed and tested on Google Chrome browser. I used the inbuilt DevTools (F12) and the 'Responsive Mode'. I used the width of 320px as the lowest common denominator in my responsive design, as this is the smallest increment in DevTools by default, so was a good starting point.

For the Desktop iteration of the site, I chose a minimum with of 1024px, another generic breakpoint featured in DevTools.

In between these points, I used the iPad Mini responsive preset to develop for the tablet offering. I made use of the ability to simulate both portrait and landscape views for mobile devices.

I prioritized my MVP for mobile, then desktop. Tablet resolutions such as the iPad Mini took a hybrid approach. As development progressed, I found that my tablet-specific wireframes weren't crucial to the experience. Instead of using development time on tailoring navigation icons and a 3 column gallery to this specific device, I saw that it elegantly could display a bigger mobile experience and smaller desktop experience in portrait and landscape, respectively.

I relied on the [GitPod Full Template](https://github.com/Code-Institute-Org/gitpod-full-template) made available by Code Institute as the basis of my code. This preconfigured all dependencies and allowed me to hit the ground running.

I set up a python3 server in the CLI which allowed me to see how my code would display in the browser. It was as simple as saving my code in GitPod and refreshing the browser - with caching disabled.

With respect to MFD, I frequently resized the browser window in DevTools to test my breakpoints. I chose relative size values for Header and Navigation elements which ensured that the presentation and flow did not break. As the nav elements are flex items, I wanted them to retain their horizontal flow without wrapping even at the smallest desktop width of 1024px.

I would test the styling of my items and iterate to ensure I got the desired presentational effect at a range of resolutions, orientations and aspect ratios. This was a great learning opportunity to improve my element targeting and value syntax skills as the project progressed.

Links were tested across pages. External links were tested to open a new browser tab. The form was tested to ensure that the browser recognized which elements were required, and that radio buttons were grouped correctly to prevent multiple selections. I tested the completed form to ensure it would send users to the Thank You Page upon completion.

Aside from the artistic and functional testing conducted by myself, I used online tools to validate the integrity of my code. They provide objective assessments to show if the code passes specification. This was a crucial step in the dev process, especially bearing accessibility in mind. Outlined below after the testing sections are the tools I used to assess that my code was valid. They are used either by inputting the code in the case of the code validators or the website URL in the case of accessibility checks. Lighthouse checks were done through Chrome's DevTools.

### Functionality Testing

The tests here were performed on a range of devices and browsers, which can be found [here.](#devices-and-technologies-used) A pass is considered to have been successful on every device configuration listed.

| Page | Test | Result |
| --- | --- | --- |
| All | Internal links go to relevant page | :heavy_check_mark: |
| All | External links go to relevant page in new tab | :heavy_check_mark: |
| All | Email and Telephone CTAs open relevant client on different systems | :heavy_check_mark: |
| All | Current page is highlighted to user in navbar | :heavy_check_mark: |

| Page | Test | Result |
| --- | --- | --- |
| Menu | Menu boards flex and wrap properly | :heavy_check_mark: |

| Page | Test | Result |
| --- | --- | --- |
| Gallery | Images scale on hover without overflowing | :heavy_check_mark: |
| Gallery | Images display and span in intended order | :heavy_check_mark: |

| Page | Test | Result |
| --- | --- | --- |
| Form | Required form elements are recognized by the browser | :heavy_check_mark: |
| Form | Only one radio button can be selected from a group | :heavy_check_mark: |
| Form | Input elements accommodate their content and placeholder text | :heavy_check_mark: |
| Form | Submit button takes user to the thank you page on completion | :heavy_check_mark: |

### User Stories Testing

As well as testing the functionality of the site, tests were conducted to ensure the user goals were met for all parties. Friends, family and colleagues that have used the site have responded positively to the presentation and found navigation intuitive.

| Client Goal | Facilitated By | Result |
| --- | --- | --- |
| Customers find the cafe | Address and Google Map CTA in footer | :heavy_check_mark: |
| Customers can place an order | Functional form, menu and telephone number provided | :heavy_check_mark: |
| Project a positive brand image | Cohesive styling and inviting language in copy | :heavy_check_mark: |
| Keep customers up to date | Up to date opening times and menu prices prominent | :heavy_check_mark: |

| 1st Time Visitor Goal | Facilitated By | Result |
| --- | --- | --- |
| To find the cafe easily | Address and Google Map CTA in footer | :heavy_check_mark: |
| To see the food available | Easy access to full menu from navbar | :heavy_check_mark: |
| To view pricing | All prices listed next to menu items | :heavy_check_mark: |
| To see the actual cafe | Hero image and gallery contain interior and exterior shots | :heavy_check_mark: |
| To see they can order online | Order page featured on navbar | :heavy_check_mark: |

| Returning Visitor Goal | Facilitated By | Result |
| --- | --- | --- |
| Place order for collection | Form allows for order collection | :heavy_check_mark: |
| Place order for delivery | Form allows for delivery address to be specified | :heavy_check_mark: |
| Find up to date pricing info | Up to date pricing in menu so they don't have to go to the cafe | :heavy_check_mark: |

| Frequent Visitor Goal | Facilitated By | Result |
| --- | --- | --- |
| Connect with the cafe on other channels | Social CTAs for Facebook and email interaction and a link to a review page on homepage | :heavy_check_mark: |
| Order for catered event | Order form provides text area for special orders for events | :heavy_check_mark: |


## Validation Testing

### HTML: [WC3 Markup Validation Service](https://validator.w3.org/#validate_by_input+with_options)
  
  <details>
  <summary>Index</summary>
  <img src="docs/val-index.png">
  </details>

  <details>
  <summary>Menu</summary>
  <img src="docs/val-menu.png">
  </details>

  <details>
  <summary>Gallery</summary>
  <img src="docs/val-gallery.png">
  </details>

  <details>
  <summary>Form</summary>
  <img src="docs/val-form.png">
  </details>

  <details>
  <summary>Thank You</summary>
  <img src="docs/val-thankyou.png">
  </details>

  <details>
  <summary>404</summary>
  <img src="docs/val-404.png">
  </details>
  

### CSS: [W3C CSS Validation Service (Jigsaw)](https://jigsaw.w3.org/css-validator/#validate_by_input)
  
  <details>
  <summary>Stylesheet</summary>
  <img src="docs/val-css.png">
  </details>
  
### Accessibility: [WAVE Web Accessibility Evaluation Tool](https://wave.webaim.org/) ~ [Browser Extension Available](https://chrome.google.com/webstore/detail/wave-evaluation-tool/jbbplnpkjmmeebjpijfedlgcdilocofh)
  
  <details>
  <summary>Index</summary>
  <img src="docs/wave-index.png">
  </details>

  <details>
  <summary>Menu</summary>
  <img src="docs/wave-menu.png">
  </details>

  <details>
  <summary>Gallery</summary>
  <img src="docs/wave-gallery.png">
  </details>

  <details>
  <summary>Form</summary>
  <img src="docs/wave-form.png">
  </details>

  <details>
  <summary>Thank You</summary>
  <img src="docs/wave-thankyou.png">
  </details>

  <details>
  <summary>404</summary>
  <img src="docs/wave-404.png">
  </details>

  I received 1 consistent WAVE alert:

  <details>
  <summary>Alert</summary>
  <img src="docs/wave-alert.png">
  </details>

  Due to there being home links on both the logo and nav elements, it flagged as a redundant link in this test. However, it would be expected by the user that clicking on either element takes them to the homepage so no changes were made.  

### [Mobile-Friendly Test:](https://search.google.com/test/mobile-friendly)
  - https://search.google.com/test/mobile-friendly/result?id=fuNWWz3m1mBr-W5qMdtvww

### Lighthouse (Open DevTools > Lighthouse)

Lighthouse reports were generated from DevTools in an Incognito Mode Google Chrome Window. I was thrilled to receive 100/100 on Accessibility, Best Practices and SEO categories. I will present mobile results first (in keeping with the design of the app) followed by desktop. The desktop audit scored extremely favourably on performance.

I made use of the results in attempts to optimize performance. For example, I made use of the preconnect feature for imported fonts as seen in [this commit.](https://github.com/jts272/pp1-happy-bees-cafe/commit/2b53a9660e5c6477e3299eb8cd51922042014ce8) I also experimented with different filetypes and pixel widths for my hero image and ultimately settled on a [2000px width jpg](https://github.com/jts272/pp1-happy-bees-cafe/commit/272049a737673c230f7d7e6106867600e5738d4c) for balance of filesize and image clarity. This is definitely a discipline I would like to further research and optimize.


<details>
<summary>Index - Mobile</summary>
<img src="docs/lh-m-index.png">
</details>

<details>
<summary>Menu - Mobile</summary>
<img src="docs/lh-m-menu.png">
</details>

<details>
<summary>Gallery - Mobile</summary>
<img src="docs/lh-m-gallery.png">
</details>

<details>
<summary>Form - Mobile</summary>
<img src="docs/lh-m-form.png">
</details>

<details>
<summary>Thank You - Mobile</summary>
<img src="docs/lh-m-thankyou.png">
</details>

<details>
<summary>404 - Mobile</summary>
<img src="docs/lh-m-404.png">
</details>

---

<details>
<summary>Index - Desktop</summary>
<img src="docs/lh-d-index.png">
</details>

<details>
<summary>Menu - Desktop</summary>
<img src="docs/lh-d-menu.png">
</details>

<details>
<summary>Gallery - Desktop</summary>
<img src="docs/lh-d-gallery.png">
</details>

<details>
<summary>Form - Desktop</summary>
<img src="docs/lh-d-form.png">
</details>

<details>
<summary>Thank You - Desktop</summary>
<img src="docs/lh-d-thankyou.png">
</details>

<details>
<summary>404 - Desktop</summary>
<img src="docs/lh-d-404.png">
</details>

---

## Version Control and Code Maintainability

[Click to view commit history for the project](https://github.com/jts272/pp1-happy-bees-cafe/commits/main)

GitHub was used for version control. With each change to the code, such as adding new sections in the markup, or styling a section, I would commit my updates using the CLI. From here, I used the push command to save the update to my repository.

Each commit serves as a snapshot in time of the code so the natural progression of the application's code is visible. Each commit is described by a brief message that describes what the update will do. 

GitHub allows comments on commits. I have made use of this feature to give more colour on the what and why of certain commits, as well as attributing ideas from other sources. Look out for the commits that have a speech bubble icon! :speech_balloon:

To ensure code maintainablility, I have used [Google's HTML/CSS Style Guide](https://google.github.io/styleguide/htmlcssguide.html) as a rubric. In short, this amounts to appropriate use of HTML5 semantic elements and meaningful ordering and naming conventions in my stylesheet. My style declaration blocks are ordered alphabetically with one exception; where positioning rules are declared, I state my positioning values clockwise from the top, mirroring the shorthand function.

As a coder at the early stages of learning, I found this very helpful to build good habits in producing 'clean code'. On top of fully passing validity checks, I want my code to be easily scannable to human readers.

Examples of best practices taken with my code include:

- Descriptive and consistent file and class names
- Lowercase naming conventions with no whitespaces between words
- Understandable directory grouping for project files
- Consistent indentation and commented section headers in stylesheet
- All styling controlled by a separate stylesheet, linked in each page's head element
- Semantic markup used in an ordered and consistent manner across pages

In keeping to these practices, my aim is to make any future updates as smooth as possible. Whether by myself or by collaboration, my code should be quickly understandable to make updates as frictionless as possible.

## Deployment Strategy

The deployment platform for this project was GitHub Pages. This was a simple process once the site was ready to go live. Here are the steps taken to deploy:

1. From the main repository page, select 'Settings' :gear: from the top tab
2. Under the 'Code and automation' section of the list on the left, select 'Pages'
3. Select the 'main' branch and 'root' folder and hit 'Save'
4. Wait for GitHub to build the webpage and follow the URL provided after processing.

By following these steps, the contents of the repository is published live to the internet. The provided URL can then be accessed from any device's browser.

![github pages deployment](docs/github-pages.png)

## Bugs

The application meets the demands of its clients and users. Functionality of the application is as intended through thorough testing. Along the way, there were a few bugs that were addressed to meet the goals of the project:

1. Footer items not flexing as intended

<details>
<summary>Footer Bug</summary>
<img src="docs/footer-align.png">
</details>

- Solution [Adjust margin shorthand values](https://github.com/jts272/pp1-happy-bees-cafe/commit/efbb25b02ba74b7136032dd24b3b8639b3c722c5#comments)

2. Form time and date not properly selectable at certain resolutions

<details>
<summary>Form Bug</summary>
<img src="docs/form-bug.png">
</details>

- Solution [Adjust width % values of input elements at 1024px width](https://github.com/jts272/pp1-happy-bees-cafe/commit/967909d374a98a13c362fda9fbc2ff143ed8dce5#comments)

3. Opening times table WAVE error

<details>
<summary>Opening Times Bug</summary>
<img src="docs/empty-table-bug.png">
</details>

- Solution [Add text to second table header and set `display: none;` with CSS](https://github.com/jts272/pp1-happy-bees-cafe/commit/596b666d5867cc3e319d85b5bfd4227f8b6bb096#comments)

## Workflow Optimizations and Future Ideas

I found this project to be a fantastic learning opportunity. As my first foray into HTML and CSS coding for a web application, there were many problems to overcome. Here are just a few things I've learned that will optimize the development of future work:

- Proper use of 'container' divs to control layout behaviour
- Ensure validity of markup of index page before creating other pages - don't copy bad code that you will have to replace in bulk!
- Improved understanding of semantic element usage
- In general, use intended capitalization in body text to prevent excessive text-transform usage
- Better understanding of how to format tables - establish a row first!
- Targeting the correct element in CSS - perhaps the biggest cause of frustration to overcome!
- Establishing general rules at the top of the stylesheet
- Proper ordering of media queries to display the site as intended

I am happy that the application met its goals in full. However, there is always more to learn and implement for the future. Here are some ideas:

- Burger menus can be implemented without JavaScript! [Example in my CodePen.](https://codepen.io/jts272/pen/BaxPdjY)
- Including further interactivity with gallery items, such as clicking will provide a text description of the image or a link to it on the menu
- Implementing a Favicon. Not a make or break feature as GitHub Pages provides a generic one, but would be expected for sites hosted independently

## Devices and Technologies Used

### Hardware

- Lenovo Windows 10 Home 14" Laptop @ 1920x1080, 100% Scaling
- Dell LCD Monitor @ 1280x1024
- LG CRT Monitor @ 1024x768
- Apple iPhone 6s

### Software

- Google Chrome - Majority of coding/testing and extensive use of DevTools and device simulation
- Mozilla Firefox Developer Edition - Used more for desktop development and robust grid viewing tools
- Microsoft Edge - Another browser for testing
- Apple Safari iOS - Mobile browser for testing
- MS Paint - Resizing images
- GIMP - Exporting images to WebP format
- Balsamiq - Wireframing
- Windows Snip & Sketch (Win + Shift + S) - For quickly capturing and annotating my screen

### Browser Extensions

- GitPod - To open templates into a workspace
- QR Code Generator - Quickly access site on real mobile hardware
- WAVE - Quickly audit accessibility features
- Webpage Spell Check - To check for any errors in the readme

### Platforms

- GitPod - The workspace in which the application was written
- GitHub - To store and host my code and application
- CodePen - To practice new coding ideas in a safe environment with instant feedback
- Pexels - For stock images
- Google Fonts - To import fonts used on the site
- Coolors - For identifying the colour palette to use for the site
- Font Awesome - For my call to action icons

## Credits and Resources

- [Code Institute](https://codeinstitute.net/) - For providing my primary learning platform and [template](https://github.com/Code-Institute-Org/gitpod-full-template), which is the foundation of this project
- [W3Schools](https://www.w3schools.com/) - My first port of call for furthering my understanding of basic HTML and CSS functionality
- [Google HTML/CSS Style Guide](https://google.github.io/styleguide/htmlcssguide.html) - To build good habits for clean coding
- [CSS in Easy Steps 4th ed.](https://www.goodreads.com/book/show/1570211.CSS_in_Easy_Steps?from_search=true&from_srp=true&qid=YEtLs5mdby&rank=1) by Mike McGrath - invaluable in getting my understanding of layout and styling up to speed
- [SEO for Dummies](https://www.goodreads.com/book/show/45004964-seo-for-dummies) by Peter Kent - Skimmed through pertinent sections to get a basic understanding of the concept
- [Essentialism - The Disciplined Pursuit of Less](https://www.goodreads.com/book/show/18077875-essentialism) by Greg McKeown - Prior reading of this helped to keep the design process properly focussed
- [Kevin Powell](https://www.youtube.com/kepowob) - My go to for CSS tutorials and exploring new possibilities
- [Jimdo Blog](https://www.jimdo.com/blog/optimize-website-images-for-better-design-seo/) - A blog for web optimization. I found the linked example regarding images helpful
- [Grace McKenna](https://github.com/gracemcken) - For letting me know that mobile-first design, grid, flexbox and Lighthouse were things that existed :pray:
- [Kera Cudmore](https://github.com/kera-cudmore) and [YatechDev](https://github.com/YatechDev) for their advice and inspiration on robust documentation :+1:

## Closing Words

It has been a highly rewarding experience to create this web application. I enjoyed the challenge of creating something inspired by a real local business, which gave me the inspiration to aim for real-world usage standards.

Although every line of code is my own, I still feel that coding is a highly collaborative discipline. No singular person knows everything and there is always more to discover. I have thoroughly enjoyed researching how to transfer my ideas to the screen for the world to see. Having a cohort of fellow code students available through Slack has created the perfect environment for sharing ideas and striving to create good work.

I will continue to follow my principles of CARE. I want to be part of making the web more accessible to all. I look forward to the new technologies I will learn and how to apply them in the future!

[Return to top](https://github.com/jts272/pp1-happy-bees-cafe#)