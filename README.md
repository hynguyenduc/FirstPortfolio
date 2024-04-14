# Portfolio Documentation

## Purpose

Hi, this portfolio is my first attempt at fully constructing a connected website with my current knowledge. The content is based on me, as it is a portfolio, but I ended up using more placeholder content to fill in the blanks. Behind the scenes, it was more about practicing the html and CSS concepts I have learned over the recent weeks.

As a portfolio, the target audience would be potential employers/customers/team members who are looking for some one with website developing skills. I used only HTMl and CSS to design and structure my website.

## Sitemap

![Portfolio Sitemap](./doc/portfolio_sitemap.png)

- Homepage is the front and also the index page
- Every page - outside the individual blogs - is connected through the navigation bar
- The logo/banner is also a link to the homepage
- 'About' page has a download link for a pdf with a mock-up resume
- 'Projects' page is currently empty due to a lack of content, but it does link to Github account site
- 'Blogs' page is more a table of blogs that link to their respective blog page
- Footer of each page also has icon links to my Github account and LinkedIn account
- I wanted every general page to be connected on each page, and if the user was curious about the blogs, they would go to the specific blog page

## Wireframe/Mock-up/Screenshots

![Mobile wireframe pt.1](./doc/Untitled_Artwork.png)

![Mobile wireframe pt.2](./doc/Untitled_Artwork_1.png)

Mobile basically used a a column display so users can scroll down and read. The logo/banner and the nav bar should take up about 1/5 of the viewport height. It remains 'sticky' to the top for easy browsing of the other pages. Information is displayed in bubble-like containers, which alternate between black and white for contrast.

![Desktop and tablet wireframe pt.1](./doc/Untitled_Artwork_2.png)

![Desktop and tablet wireframe pt.2](./doc/Untitled_Artwork_3.png)

![Desktop and tablet wireframe pt.3](./doc/Untitled_Artwork_4.png)

With tablet and desktop, comes the landscape option. This allows the content to spread out horizontally. However, the banner/navbar and footer sections still have the same purpose. Only difference is that more text/information containers can be positioned on screen before scrolling. However, when tablets are turned onto portrait orientation, I made it so it transitions to a scaled up version of the mobile display.

The end result is similar to the initial design.

## Functionality, features and components

Banner: contains img and link elements to act like another homepage button. It is pinned to the top of the page, even when you scroll down the page on phones/tablets. When the home page has more content i.e. more updates posted, it would serve as a easy to click function to take the user to the home/index page.

Blog: contains headings, img and/or paragraph elements to house content. The blogs with img have a link to open up a more high quality version, if appicable. Its just a simple display for content, and the black and white alternating color scheme add contrast to draw in the user's eye. It can also house a smaller image to draw user's attention.

Navigation Bar: contains links and spaced evenly with css grid. Sticky positioned to top of page, even when you scroll down the page on phones/tablets. Makes all the pages permanently in sight of the user to help with browsing the site.

Social: contains links and img elements. This is always at the end of the page. The icons are clickable links that take the user to my Github and LinkedIn if they want to see my work/work history. The links open into a different tab, so the user can still continue browsing the portfolio. Remains at bottom of the page no matter how long the content (more so for the mobile version). Just links user to more official sources of my work/work history.

## Github REPO
https://github.com/taijitsuhitsyou/FirstPortfolio