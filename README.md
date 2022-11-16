# Portfolio Website Documentation

## Links
- [Portfolio Website](https://earnest-cajeta-a61125.netlify.app/blog4.html)
- [GitHub Repository](https://github.com/johnsonw1017/Portfolio)
- [Website Presentation Video](https://youtu.be/PjXmvx4T7vE)

## Purpose
The target audience of this website is potential employers and colleagues. It is an opportunity introduce my background, experience, personality and interests and to showcase my web development skills.

## Sitemap
This website has a very simple sitemap. The home page contains all information regarding my interests, resume and links to recent blog posts. I wanted all this information to be found in my home page so that the audience can know me at a glance without having to navigate. The home page links to the 6 blog posts (html pages) and other posts can be navigated from each blog post. 

![Sitemap](/docs/sitemap.jpg)

## Wireframe
The following are screenshots of the wireframes for the home page and the blog post (all 6 blogs will follow the same format). The look of the website on different screen sizes is also shown. The features will be discussed in the *Feature and Functionality* section.

![Home page Wireframe](/docs/HomeWireframe.png)
![Blog page Wireframe](/docs/BlogWireframe.png)

## Aesthetics
The main colours used for the website is <span style="color:black; background:white">black</span>, <span style="color:white; background:black">white</span> and <span style="color:red">red</span>. The choice of the colour scheme is for a simple and classic look of the website. Black is used for the navigation bar, white for content background and red is used to highlight content such as the resume button and some texts. I kept the background white to make the images and red text more noiceable.

The font-family used for this website is [Lora](https://fonts.google.com/specimen/Lora)from Google Fonts. The font also adds to the classic look of the website.

## Layout
The header and footer of the website are across 100% of the screen width. The main content in the body has a maximum width of 1024px. In the case where the screen is larger than 1024px, the extra width would be white background. All content are within containers that left and right margins set to auto, which allows the content to be centred along the horizontal axis of the screen.

The screen widths which each component of the website take is specified by utilising a 12-grid system (see below image). The 12 grid system is one which the width of the container where the content is, is divided into 12 grid-lengths. For example, if you wanted to displayed 2 componments in the same container (row) you can set the width of the componments to take up 8 columns and 4 columns of the screen respectives. Or in another case you wanted to show 3 components on the same row with equal lengths, then each component would be 4 columns width. The 12-grid system utilises Flexbox in CSS and class specificty to alter the widths of the components. It provides a guideline in which the content would be displayed and accounts for changes in the screen size as well.

![12-Grid System](/docs/12-grid-system.png)

## Features and Functionality
Features of the Home page and the blog pages would be discussed in sequential order.

1. Navigation bar: this bar shows navigation links as well as my social links. "Home" links to the home page and "Blog post" links to the bottom of the home page where there is a selection of blog posts.
2. Introduction section: in this section a picture of my face is shown and below an introduction about myself. When the screen width is above 768px the photo would be on the same row as the intro at 4 columns and 8 columns respectively.
3. Interests section: this section outlines my hobbies and interests and showcases a bit of my personality. The main points at highlighted in red to give the audience some descriptive words about me. Each of the boxes are of equal width. And at media breakpoints would show 1 to 3 boxes to accommodate for screen sizes. When hovered, the icons would swing infinitely.

![Home page 1](/docs/Home1.png)

4. Resume button: once this button is clicked, a pdf document of my resume would show up on the screen.
5. Blog post section: shows a list of blog post and their publish dates. Each boxes display the title image and the title of the blog post. Same as the interest section, the 1 to 3 boxes will show in a row at 2 media breakpoints. Each of boxes links to the blog post when clicked.
6. Footer: shows logo and a copyright claim.

![Home page 2](/docs/Home2.png)

7. Blog post title card: just a large version of the Blog post section boxes.
8. Comment and share button: The comment button links to the comment section of this page, the share button is non-functional but links to a definition page for the word 'share'.
![Blog page 1](/docs/Blog1.png)

9. Comment section: this section allows user input. The submit button is non-functional.
10. Other posts section: same as the blog post section without the current post.

![Blog page 2](/docs/Blog2.png)

## Tech Stack
This website was made with HTML and styling through CSS. Website was deployed through Netlify.