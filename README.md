# PP 1

In this section, you will include one or two paragraphs providing an overview of your project. Essentially, this part is your sales pitch. At this stage, you should have a name for your project so use it! Don’t introduce the project as a Portfolio project for the diploma. In this section, describe what the project hopes to accomplish, who it is intended to target and how it will be useful to the target audience.

## Intro

why and what

![Responsive Mockup]

## Features

### Menu Toggle

  - This function is intended to improve the user experience on mobile devices and tablets.
  - Even though it is a common practice here to use an icon from e.g. Fontawesome, I decided to create the burger buttons with vanilla CSS.
  - To do this, I gave three span elements the necessary styling in CSS.
  - On mobile devices, the menu button allows the navigation bar to slide in vertically in a narrow version so as not to cover the entire screen.
  - On tablets, the navigation bar slides in horizontally to cover as little of the content as possible.
  - On devices larger than 992px, the menu button disappears, and the navigation is traditionally displayed in the header.
  - The navigation bar is also slightly indented on very large screens to achieve a better display.

    ![Menu-mobile](assets/images/menu-mobile.png) ![Menu-tablet](assets/images/menu-tablet.png) ![Menu-desktop](assets/images/menu-desktop.png)

### Scroll To Top Button

  - Designed in the Main Colour Theme of HTML, CSS, and JavaScript Brand colours
  - The Button appears at Scroll Down further than 120vh and is sticky at the bottom of the content.
  - The Element presents him self in the HTML Colours due to his position in an HTML element.
  - “On Hover” The Button becomes his action colours for style and function represented by Background-colour of JavaScript and icon-Colour of CSS. 
  - Even if the function was not implemented with JavaScript, it is still a suitable analogy to the basic interaction of the three components.
  - In addition I added a scroll-behavior of smooth so that the page can be better perceived.

    ![Scroll to Top Button - passiv](assets/images/sttop-passiv.png) ![Button Activ on Hover](assets/images/sttop-active.png)

In this section, you should go over the different parts of your project, and describe each in a sentence or so. You will need to explain what value each of the features provides for the user, focusing on who this website is for, what it is that they want to achieve and how your project is the best way to help them achieve these things.

### Existing Features



For some/all of your features, you may choose to reference the specific project files that implement them.

In addition, you may also use this section to discuss plans for additional features to be implemented in the future:

### Features Left to Implement

- Another feature idea

## Testing

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your project’s features and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.

### Validator Testing

- HTML
  - No errors were returned when passing through the official [W3C validator]
- CSS
  - No errors were found when passing through the official [(Jigsaw) validator]

### Solved Bugs

- #Issue 01 - The first grid layout didn't work as desired.
- #Issue 02 - The Elements in the footer have not aligned correctly.
- #Issue 03 - The Empty main Section caused an overflow to the whole site
- #Issue 04 - The Navbar-links caused an overflow to the right on larger screens.
- #Issue 05 - The hidden checkbox in the header to control the menu bar via the burger icon causes the menu links to shift to the right when clicking in the header area on larger screens (laptop and up).

### Unfixed Bugs

You will need to mention unfixed bugs and why they were not fixed. This section should include shortcomings of the frameworks or technologies used. Although time can be a big variable to consider, paucity of time and difficulty understanding implementation is not a valid reason to leave bugs unfixed.

## Deployment

The website was deployed using GitHub Pages by following these steps:

- The site was deployed to GitHub pages. The steps to deploy are as follows:
   1. In the GitHub repository, navigate to the Settings tab
   2. From the source section drop-down menu, select the Master Branch
   3. Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.

The live link can be found here - [Stundent-X](https://lorenz-127.github.io/pp1-v3/)

## Credits

- Font-awesome Icons from [fontawesome.com](https://fontawesome.com/icons)
- This favicon was generated by [favicon.io ](https://favicon.io/favicon-generator/)

In this section you need to reference where you got your content, media and extra help from. It is common practice to use code from other repositories and tutorials, however, it is important to be very specific about these sources to avoid plagiarism.

You can break the credits section up into Content and Media, depending on what you have included in your project.

### Content

- Slide-in navbar and
- Burger menu

  The inspiration for these two features came to me during class. On the one hand, I wanted a burger menu, but not a copy of the Love Running tutorial.  I also wanted to avoid a simple solution with JavaScript and implement the function with vanilla CSS. From the lesson on UX design, I then had the idea for the slide-in menu to deviate sufficiently from the original from the walkthrough project. 
  I got the inspiration from https://www.w3schools.com/howto/howto_js_sidenav.asp and this is my attempt to implemented it without JavaScript.

- "Scroll To Top" Button

  This feature caught my attention when looking through example projects, shown by our cohort facilitator, where such a button was missing, in addition I added a scroll smooth so that the page can be better perceived. Again, I found what I was looking for on W3School. There was only one example with JavaScript, but it gave me enough information to implement the element myself in vanilla CSS.


- The text for the Home page was taken from Wikipedia Article A
- Instructions on how to implement form validation on the Sign Up page was taken from [Specific YouTube Tutorial]

### Media

- The photos used on the home and sign up page are from This Open Source site
- The images used for the gallery page were taken from this other open source site

Congratulations on completing your Readme, you have made another big stride in the direction of being a developer!

### Acknowledgements

- My Peers in Code Institute's Slack channels for their feedback and support.

### Honourable mentions

- Dimitris for his moral and technical support [LinkedIn](https://www.linkedin.com/in/dimitrios-thlivitis/) [GitHub](https://github.com/Dimitris112)
- Vernell for his valuable and patient advice on the right way to solve the problem [LinkedIn](https://www.linkedin.com/in/vernellclark/) [GitHub](https://github.com/VCGithubCode)

## Other General Project Advice

Below you will find a couple of extra tips that may be helpful when completing your project. Remember that each of these projects will become part of your final portfolio so it’s important to allow enough time to showcase your best work!

- One of the most basic elements of keeping a healthy commit history is with the commit message. When getting started with your project, read through [this article](https://chris.beams.io/posts/git-commit/) by Chris Beams on How to Write  a Git Commit Message
  - Make sure to keep the messages in the imperative mood

- When naming the files in your project directory, make sure to consider meaningful naming of files, point to specific names and sections of content.
  - For example, instead of naming an image used ‘image1.png’ consider naming it ‘landing_page_img.png’. This will ensure that there are clear file paths kept.

- Do some extra research on good and bad coding practices, there are a handful of useful articles to read, consider reviewing the following list when getting started:
  - [Writing Your Best Code](https://learn.shayhowe.com/html-css/writing-your-best-code/)
  - [HTML & CSS Coding Best Practices](https://medium.com/@inceptiondj.info/html-css-coding-best-practice-fadb9870a00f)
  - [Google HTML/CSS Style Guide](https://google.github.io/styleguide/htmlcssguide.html#General)

Getting started with your Portfolio Projects can be daunting, planning your project can make it a lot easier to tackle, take small steps to reach the final outcome and enjoy the process!