# NBM-Homework-02-PersonalPortfolio

MY USER STORY


AS AN aspiring web developer

I WANT to create an articulate portfolio website showcasing work samples and side projects such as YouTube and Twich

SO THAT I can display my web development skills with a focus on optimization and accessibility for all users

SUPPLIED USER STORY

AS AN employer

I WANT to view a potential employee's deployed portfolio of work samples

SO THAT I can review samples of their work and assess whether they're a good candidate for an open position



I began this process by creating an index.html sheet, and an assetts folder holding my style.css sheet and referenced images.

Once I had created the blank template, I used the previous assignments code as a reference for structuring my header, body, content, and footer sections.

Before adding style elements through css, I chose to fill out as much text content in my About Me, and Contact Me info as I could before moving on to design elements.

Once I started the design process with css, I considered what colors I wanted to use that would be eye catching, but not overbearing. I believed a monochrome colorway would do well with contrasting colors and having the darker colors emphasize the content I wanted users to focus on the most. 

With my only colors being black, gray, and white, I considered using an accent color to add some additional flair without compromising the monochrome focus. I chose corn flower blue for the accent color as it reminded me of the colors used by my favorite e-sports organization, Cloud9.

Next, I wanted to give content sections some separation from the sides of the screen to avoid a visual feeling of a verticle barcode. To achieve this, I adjusted the border radius of my content sections (and eventually my displayed images) to 25px to round off the edges. 

To add additional flair, I implimented a corn flower blue box shadow on my header, images, content, and footer sections. I was surprised to notice that the additional usage of blue did not compromise the overall monochrome asthetic. 

My next step was to create a fixed header that followed the user as they scrolled down the page. The header also featured nav links which would direct users to specific sections upon clicking the words. 

After creating nav links to my About Me, My Work, and Contact Me sections, I decided to create an additional nav link that would return the user to the top of the page. This would allow the user to reach any point of the page directly from the nav bar in the header. 

Though I used the "Gill Sans" font family for my base text, I thought that the "Impact" font family did a good job of differenciating h1 and h2 tags from the main content and paragraphs.

Now that I had done basic styling for my text-heavy content sections, I decided to add images of myself between each section of text content to space out the website better and allow for better focus when a nav link was clicked. 

This ended up being one of my biggest challenges as my images all had different pixel sizes, creating large amounts of gray space and inline-block indentation. 

To correct this, I formatted my image groups with display:flex, flex-direction: row, and justify-content: space-between to evenly space out my images into same size columns. 

At this point I started to get the feeling that I was approaching the finish line of my base web browser design, but after stepping away from my code for a while, I began to think of ways that I can add some more "pop" to the page.

My first idea was to create three buttons in my footer tag which would direct the user to some of my other pages like my Twitch channel, YouTube channel, and my LinkedIn profile. 

Once the buttons were functional, I decided to add a hover effect which would change colors to further emphasize to the user where they will be directed upon clicking the button. 

With a fixed header I noticed that my nav links would push the content to the top of the page, but would cut off about half of the content by being covered by the fixed header. To correct this, I created anchor points above each section of content with an absolute position and a pixel buffer to give space for the content and the header.

Finally, I added another styling element to the header/nav bar where when the user hovers over a specific nav link, the text color would change from mint cream to corn flower blue while the font family changed from "Gill Sans" to "Impact."

The next step was to format the site to be usable on mobile devices. I started this process with a media query and attempted a few different max-width values to use as a catch all for most mobile device screen sizes. 

This step proved to be the most challenging of them all as I found discrepancies between the mobile view in my devtools and it's actual appearance on my mobile device. 



[DeployedPortfolioApplication](https://nathanmilburn.github.io/NBM-Homework-02-PersonalPortfolio/)
[DeployedPortfolioRepository](https://github.com/NathanMilburn/NBM-Homework-02-PersonalPortfolio.git)