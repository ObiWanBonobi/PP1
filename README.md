# Fabian Schwabegger

![Home page gif](assets/gif/Home-page.gif)

[Click on this link to visit the website](https://obiwanbonobi.github.io/PP1/)

<br>

# Content

- [Introduction](#introduction)
    * [User experience](#user-experience)
    * [My vision for the website](#my-vision-for-the-website)
- [Features](#features)
   * [Navigation](#navigation)
   * [Footer](#footer)
   * [Collaborations navigation](#collaborations-navigation)
   * [Home Page](#home-page)
   * [Collaborations page](#collaborations-page)
   * [Contact page](#contact-page)
   * [Contact send page](#contact-send-page)
- [Future features](#future-features)
- [Design](#design)
- [Technologies used](#technologies-used)
   * [Balsemiq](#balsemiq)
- [Testing](#testing)
    * [Validation HTML and CSS](#validation-html-and-css)
- [Credits](#credits)

<br>

# Introduction

I embarked on the journey of creating a website for my partner, who is a graphic designer, with a profound sense of purpose. Recognizing his extraordinary talent as a graphic designer, I wanted to offer a dedicated platform that would not only honor his work but also provide a showcase for his remarkable skills. This website stands as a testament to our shared commitment to creativity and design excellence. It's a space where his artistic endeavors can shine and captivate, where clients can discover the transformative power of design. 

By crafting this online presence, I aim to assist in amplifying his reach and connecting him with a broader audience that appreciates the craftsmanship and ingenuity he brings to every project. It's a digital canvas where his talents can truly flourish, and I'm thrilled to contribute to this creative endeavor that continues to inspire us both.

![readme cover image, Black Chinchilla product](assets/images/readme_images/black-chinchilla-product.webp)

## User experience

I've meticulously crafted this online space to ensure a seamless and engaging user experience. Ultimately, I want visitors to my website to feel inspired, informed, and connected. Whether they're seeking my partner's services, admiring his work, or just exploring the world of graphic design, I aim to provide an exceptional and memorable user experience that leaves a lasting impression.


## My vision for the website

The layout is intuitive and visually appealing, making it easy to navigate through and explore his work. I've optimized the site for all devices, ensuring that whether on a desktop, tablet, or smartphone, the content remains accessible and aesthetically pleasing. I've paid close attention to loading times to keep the user engaged and prevent frustration. 

Whether it's the captivating visuals or the carefully crafted text, I've strived to create a harmonious blend that provides valuable information. In addition, I've included a user-friendly contact form, and Fabian is committed to a swift response. I've placed a strong emphasis on accessibility to ensure that everyone, regardless of ability, can enjoy the site without barriers.

<br>

# Features

### Navigation

The navitagion bar is always visible at the top of each page, for easy navigation. It includes :
- on the left side are Fabi's initials on small screens and his full name on bigger screens
- on the right side is a burger icon on small screens and the full navigation menu on bigger screens
- I gave the navigation bar a barely visible line underneath to show a difference between navigation bar to the main section

![Navigation on small devices](assets/images/readme_images/navigation-on-small-device.png)
![Navigation on medium devices](assets/images/readme_images/navigation-on-medium-device.png)
![Navigation on large devices](assets/images/readme_images/navigation-on-large-device.png)

### Footer

The footer is at the bottom of each page and it includes a link to Fabian's instagram account. I gave the footer bar also a barely visible line above to show a difference between the footer and the main section.

![footer](assets/images/readme_images/footer.png)

### Collaborations navigation

On the left top side in the Collaborations page, I've added a "go down" icon that navigates to different collabs in the page. This helps move around quicker and more clearly.

![Collab navigation](assets/images/readme_images/Collab-navigation-tool.png)

### Home page

I've kept the design of the home page simple. 
- My train of thought was to have Fabian's designs to be the main attraction throughout the website. 
- In the second paragraph, the collaborations bubble, I added a link to the collaborations page.

### Collaborations page

- Same as the home page, I wanted to keep Fabians desings the main attraction. 
- On the left top side is a down arrow to navigate through fabians designs.
- Every picture in each < div > is cropped to the same size, to keep the page looking clean.
- I seperated some of the desings in different < div > so when they are shown on bigger screens, they stay together.

### Contact page

- The contact page includes a form that can be filled out to get into contact with Fabian.
- It also includes a map of where Fabian is based.
- After you press the send button, you will be taken to a new page that says thank you.

### Contact send page

- This page will only show after you filled out the contact form.
- It has a short thank you message with another desing.
- It was the same layout as the other pages so you can easily navigate back to the other pages.

<br>

# Future features

I want to add javascript to all pages and make the whole site more interactive.
- I want to add a zoom in feature for all pictures
- I want to make a "entry" page with a large design that will take you to the main website when you first load the website
- I want to make the pages move right to left when you go to the next page to the right. And left to right when you go to the previous page.
- Add more collaborations
- I want to improve the collaboration navigation

<br>

# Design

- <b>Font</b> : With the help of the Code Institute, Love running project, I got my font from [google fonts](https://fonts.google.com/)
- <b>Icons</b> : Also with the help of the Love running project, I used the [Font Awesome](https://fontawesome.com/) website
- <b>Favicon generator</b> : I made my own favicon with [this website](https://favicon.io/)
- <b>Map</b> : I used [Google Maps](https://maps.google.com/) for the small map on the contact page
- <b>Image resizing</b> : I used this [Image resizer](https://imageresizer.com/) website to change my images
- <b>Gif</b> : I used [this website](https://ezgif.com/) to create a gif for my README


### Colour scheme

I kept the colour scheme very simple, because I wanted Fabian's designs to pop out.

![Colour Scheme](assets/images/readme_images/color-scheme.png)

<br>

# Technologies used

- The website is written in HTML and CSS only
- I did all my coding with the program VS Code, [Visual Studio Code](https://code.visualstudio.com/)
- All my code was uploaded to [Github](https://github.com/), to my [Github account](https://github.com/ObiWanBonobi)

### Balsemiq

<details>
<summary>The project started with Balsamiq, where I imagined the beginning of the website on all device sizes. I did end up deviating from the original imagination on balsemiq.</summary>

![Balsemiq](assets/images/readme_images/balsamiq-index-page.png)

![Balsemiq](assets/images/readme_images/balsamiq-collaborations-page.png)

![Balsemiq](assets/images/readme_images/balsamiq-contact-page.png)

![Balsemiq](assets/images/readme_images/balsamiq-contact-send-page.png)

</details>

<br>

# Testing

Every link on all pages got tested on several devices and webbrowsers. The contact form has been tested as well and works as it should.

### Validation HTML and CSS

<details>
<summary>The home page had an initial error with the < footer > where I had put an < p > in a < ul ></summary>
<img src="assets/images/readme_images/index.html-1st-test-with-error.png" name="Html index validation">
<img src="assets/images/readme_images/issue-with-index.html.png" name="Html index validation">
<img src="assets/images/readme_images/index.html-issue-fixed.png" name="Html index validation">
<img src="assets/images/readme_images/index.html-fixed-and-validated.png" name="Html index validation">
</details>

<details>
<summary>The collaborations page also had an initial error where I had put my collab navigation in a < section > instead of a < div ></summary>
<img src="assets/images/readme_images/collaborations.html-1st-test-with-error.png" name="Html Collaborations validation">
<img src="assets/images/readme_images/collaborations.html-issue.png" name="Html Collaborations validation">
<img src="assets/images/readme_images/collaborations.html-issue-fixed.png" name="Html Collaborations validation">
<img src="assets/images/readme_images/collaborations.html-page-fixed-and-validated.png" name="Html Collaborations validation">
</details>

<details>
<summary>The contact page had no issues from the start</summary>
<img src="assets/images/readme_images/contact.html-good-and-validated.png" name="Html Contact validation">
</details>

<details>
<summary>The contact send page did not have any issues as well</summary>
<img src="assets/images/readme_images/contact-send.html-good-and-validated.png" name="Html Contact send validation">
</details>

<details>
<summary>The CSS file did not have any issues as well</summary>
<img src="assets/images/readme_images/css-validation.png" name="CSS validation">
</details>

### Lighthouse test

<details>
<summary>The home page had an initial error where I had used < h3 > where I shoul've used a < h1 >. After I changed that it came back with this result :</summary>
<img src="assets/images/readme_images/lighthouse-test-index.png" name="Lighthouse home validation">
</details>

<details>
<summary>The collaborations page also had an initial error where I had used < h3 > where I shoul've used a < h1 >. After I changed that it came back with this result :</summary>
<img src="assets/images/readme_images/lighthouse-test-collaborations.png" name="Lighthouse collaborations validation">
</details>

<details>
<summary>The contact page didn't have any issues :</summary>
<img src="assets/images/readme_images/lighthouse-test-contact.png" name="Lighthouse contact validation">
</details>

<details>
<summary>The contact send page also didn't have any issues :</summary>
<img src="assets/images/readme_images/lighthouse-test-contact-send.png" name="Lighthouse contact send validation">
</details>

### Testing on different devices

I tested the deployed wedsite on several devices webbrowsers :
- Iphone 14
- Ipad gen 3
- Google pixel 7
- Samsung galaxy tab S6
- HP envy 
- PC build

<br>

- Google chrome
- Microsoft edge
- Apple Safari

<br>

# Credits

- <b>Layout, contact form and code</b> : the navigation and footer layout, the contact form code and some of the basic code I partly got from the Code Institute learning program and projects, [Love Running](https://github.com/Code-Institute-Org/love-running-2.0) and Coding Coffee House
- <b>README</b>> : a bit of the layout from the Code Institute Coding club sample, and from Siobhan Gorman's project [Sourdough Bakes](https://github.com/siobhanlgorman/Sourdough-Bakes)
- <b>README funtions</b> : got some ideas from cosmiccoincidence's [README](https://github.com/RE-SS3D/.github/blob/main/profile/README.md)
- <b>Images</b> : All images come directly from Fabin Schwabegger
- <b>Gif</b> : I got the gif in the readme idea from stumbling upon [this website](https://medium.com/@alenanikulina0/make-your-readme-better-with-images-and-gifs-b141bd54bff3)

- <b>most of my credit goes to the Code Institute program where I made notes on every section and got most of my ideas and code from there.</b>