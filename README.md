# WeekOneHomework
01 HTML CSS Git: Code Refactor

**Version 1.0.0**

## Task Description
The task was to refactor the supplied code to meet basic web accessability standards. These standards are used by Web Developers to ensure people with disabilities or Socio-economic restrictions have access to websites. I have followed <a href="https://www.w3.org/WAI/standards-guidelines/wcag/">Web Content Accessability Guidlines (WCAG)</a> found on the  Web Accessability Initiative (WAI) website, when refactoring the code.

## Prefix
When refactoring this website, I was working with a large monitor size and basing the styling for the website using my personal browser size. I have since learnt that this is not suitable practice for Web Development, however for this particular week one homework assignment I have not made any further updates to my styling to meet a standard sized screen. This means that if you are viewing my work on a smaller monitor (or browser window) than what I have used, the website will not be formatted properly.

I have used a browser size of 1920px X 969px to re-design this website. 

I have included an image below of how the website looks in my browser. I understand that this homework assignment is more focused on the HTML/CSS code rather than browser responsiveness, however when referring to my work later in this ReadMe I will be basing it off the image below.

![](assets/images/Website-Viewed-At-1920x969-pixels.png)

## Tidying up the code

The given HTML & CSS documents featured a lot of unnecessary, inefficient and buggy lines of code. Some examples of this were broken links in the nav bar, repeating CSS and inproper indentation. I first went through and tried to fix all the small errors I could see whilst also reformatting the indentation of the HTML code. I then turned my attention to the CSS code and tried to make the code more effecient and easier to read by grouping repeating lines of CSS where appropriate. 

## Following Web Content Accessability Guidelines (WCAG)

In this section of the ReadMe I will outline the major changes I made to the website and the WCAG theory that provoked these changes to be made.


#### Adding "alt" tags

Alt tags are used to convery the purpose of an image for users who do not see the image. Users not being able to see the image on their screen can be down to a number of factors, however the most common of these are due to the person being visually impaired or having turned images off to increase download speed or save bandwidth.

When a person cannot see the image, the alt text can be played using a screen reader. The hero image was purely decorative so no alt tag was needed. The other images supported what the text was saying, so I decided to an alt tag for these.

#### Colour Contrast, Font Family & Font Size

Some users cannot read text when the contrast between the colours is insufficient. The website was originally using white text against a light-medium blue background, which did not meet WCAG standards. I changed the background colour to a darker, more subtle soft-blue which made the white text easier to read due to the contrast. I also added a soft brown colour for some images to make them look nicer and fit a colour scheme theme I created. I added the same colour in the "seo" letters of the logo and as a hover colour for the links in the nav bar.

I changed the font family and font sizing throughout the page to make the text easier to read. The only text I made harder to read was the footer text, as this is non-essential information for the average user.

#### Reformatting the Page

I made numerous changes to the styling of the page in regards to margins, padding and spacing so that each section and sub-section of content was easier to read. As noted in the Prefix, I styled the page based on my monitor size, which I have now learnt is not the correct method for future projects. As seen in the image above, each section & sub-section can clearly be defined with adequate spacing and padding between them. Originally, the sidebar sub-sections were quite close together and the page did not line up, which was something I tried hard to fix. I also took into consideration the height of the navbar and the horizontal margin between links, making sure enoughs space was between them so they can properly be identified/read.

## License & copyright

© Chris Roschi, University of Adelaide Coding Bootcamp
