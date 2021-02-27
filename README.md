*Code Institute / Milestone Project 1: User-Centric Front-End Development*

# WELCOME TO EWAN JAMES MUSIC!

![ Logo for Ewan James Music ](assets/images/ejm-logo.jpeg)

### This is the one and only official site for all things related to Ewan James' music.

Ewan is my son and an aspiring musician who writes, produces and plays his own original songs. Although present on some social media sites, he wanted
 me to design him a website to channel all these mediums in one place and begin building up his name and brand.
 
From his website, a visitor can signup
for exclusive email updates, find the latest gig locations and dates, buy tickets, download the latest music by Ewan James, see pictures from his
musical journey or watch his latest youtube videos.
 
The milestone project required me to design and build a website with at least three pages or
page sections for a real or ficticious band. In this case I decided that since Ewan needed a website designed to help promote his songs that this is
what I would do for the project and he agreed.

___

## UX

**STRATEGY & SCOPE:**

After discussions with Ewan on what he wanted to achieve by having a website plus what he expected a visitor to the site to find and how they would
interact with the site, he decided on the following:

**Goals set by the website owner:**

1. Build brand awareness of EJM logo to represent his music.
2. Consolidation of social media presence.
3. Build a database of fans to directly contact via email subscriptions.
4. Use the website to advertise and distribute his own music.
5. Sell official merchandise and tickets.

**Goals set for the user:**

1. Download new music by Ewan James.
2. Receive email newsletters about Ewan James.
3. Find out more about Ewan James and his equipment.
4. Watch videos by Ewan James.
5. Buy official merchandise and tickets.

Since Ewan is a teenager himself and writes songs about the highs and lows of being a teenager, his target audience would be women between the ages of **from 15 to 25** and other musicians as his
potential audience. Therefore, the social media links should be prominent on every page of the site as this is how he believes his target audience
predominantly communicate.

**STRUCTURE:**

Ewan doesn't have much content for his website yet as he is just starting out, so we decided to keep the structure simple:

1. Home Page.
2. About Me Page.
3. Downloads Page.
4. Signup Page.

The home page would be clicked to from all other pages by the logo in the centre-top of each page. To emphasize where the user is on the site, the border of
the logo would be emphasized in the #daa520 on the home page only, which would be consistent with all other pages since they would all use the 'active' class 
to reinforce which page the user is on.

The content for each page would be supplied by Ewan. The layout would be a simple 'welcome' message, then the callout to signup followed by his latest you-tube recording.

The about me page would be more detailed. To follow the header, the callout will be next with the page title underneath it and content. The page will be broken
down into three sections: History, My Guitars, My Equipment. Each section will have anchor links to move directly to that section of the page or move back to
the top of the screen.

The downloads page would have the same callout as the about me page following the header, the page title underneath it and then a section for each song-release
with it's title as a sub-header and links to Apple and Google for downloading these.

The signup page does not need the callout at the top so this will be a header leading into form cells. The page will have a picture in the background and
allow space for more images, videos etc. to be added in the future to emphasize the exclusive content and news that users could get based on previous
information.

All pages should have a 'back to top' button at the bottom-centre of the page if the user needs to scroll down to see more content on that page.

**SKELETON:**

The wireframes for each webpage were created using the 'Balsamic' software and follow the basic design rules decided on in the 'Structure' phase. The wireframes
were each saved in a .png format and attached with this repository in a separate folder called 'wireframes' to view.

## DESIGN

Each page should have a different picture at the top of Ewan or his equipment to emphasize to the user that they are on a different page. Also, after the header
(which will contain the logo, navigation and social media links), with the expection of the signup page, the first section underneath should be a callout to get 
the user to signup their email address to receive updates. Then the main page title and content should follow.

After discussions with Ewan about his favourite colours, he decided that he wanted to have the standing theme for text running throughout the website as a
deep blue. Unsure of the blue colour used in his logo design, I asked him to look at a selection of hex colours in Adobe Photoshop and he liked #2712ab.
He also liked 'goldenrod' so we looked up the hex colour for that using google and settled on using #daa520 for the hover effects on the nav selections. Again,
to keep consistency, we decided that the social media icons would all be in the same blue as the text and the same goldenrod for the hover effects.

We decided that the best looking font for the site would be 'lato' from 'googlefonts'. All navigation pages would be in uppercase to stand out, each with a
goldenrod (#daa520) hover effect.

It's common practice for modern websites to have their logo as the home page in the navigation and no other 'home' nav to select, so we decided to do that with
his 'EJM' logo. The main difference was that he wanted his logo in the centre-top of the page and not the left. For added consistency, all the pages in the site 
will have the navigation layout identical.

**Design (Skin) Amendments:**

Whilst building the site, I became aware that it looked very basic, so after consulting with Ewan we decided to add a background picture to
the home page and change the menu and navgation to fixed position so that the rest of the page would scroll whilst the background and menu stayed the same. These
effect were liked by Ewan so we decided to use the same effects accross all four pages.

## FEATURES

Nine main things were identified as the features that Ewan wanted on his website. These were:

1. EJM brand logo on every page.
2. Links to all his social media pages.
3. 'Signup' page for email contact database.
4. 'Download' page for songs.
5. 'Shop' page for selling merchandise.
6. 'Webchat' facility to communicate with fans via the website.
7. 'About Me' biography with his life-story (so far).
8. 'Book Me' link for booking gigs.
9. 'Buy Tickets' link for selling tickets to fans.

These features were simplfied and categorised for importance and viability/feasability on a scale of 1-5 as per the lesson on 'UX Strategy Tradeoffs'.
The results were as follows:

Features              | Importance | Viability/Feasability
----------------------|------------|----------------------
1. Social Media Links | 5          | 5
2. Email Signup       | 5          | 3
3. Audio Downloads    | 5          | 5
4. Merchandise Sales  | 3          | 1
5. Webchat            | 2          | 2
6. 'Book Me' facility | 4          | 3
7. Video links        | 5          | 5
**TOTALS**            | **29**     | **24**

The results showed that the features of highest importance, viability and feasibility were items 1, 2, 3 and 7 so these should all be included in the
site. Item 6 would be added if time and resources allowed.

**Features left to implement:**
Item 5 was not important enough or able to be achieved within the timeframe set to complete the project. Item 4 was mildly important with a score of 3,
but since there is currently no merchandise available and I don't have the skills/resources to setup an online shop then this was considered as a
future improvement to the site.

## TECHNOLOGIES USED

* HTML5 - This was used to create the 'shell' or main structure of each webpage.
* CSS3 - Cascading Stylesheets to create the look of the site such as colours, typography and image display.
* Bootstrap V4.6 - Styling plugins to speed up the process of coding and add 'straight-out-of-the-box' code for specific features of the webpages.
* Font Awesome V5.15.2 - This link is for adding icons to the webpages.
* Googlefonts - Used to select and implement fonts throughout the webpages.


## TESTING

For testing the responsiveness on various different devices I used the website www.responsinator.com. This helped me to decide what size devices to put into my
overall responsiveness testing spreadsheet. I also used http://ami.responsivedesign.is/# to take screenshots on the four most-common devices to view my webpages
on one image.

I created 2 spreadhsheet to maintain continuous testing throughout the course of creating this project but quickly found that the first sheet was both time-consuming 
and duplicating the information in the commits on the repository. Instead I chose to adopt a 'change-it, test-it, commmit-it' stance and put notes in the commit on 
the repository if there was anything that I either needed to make clearer than the commit message or if there were outstanding bugs to fix later. 

The second was a more detailed spreadsheet designed to test the validity of the code on each page and also the responsiveness on multiple different viewing platforms
and web browsers. This was similar to a testing process created by former student of the Code Institute, Tim Nelson and I re-created and adapted it to work with the
contents of my website and testing so as not to copy his work directly.

Both sheets are in the directory labelled 'testing' in this repository for you to view.

## DEPLOYMENT


## CREDITS
* Photos were supplied by Ewan Brown (Ewan James) along with the audio and social media links.
* Biography of Ewan was written by him and then modified by me to suit the needs of each page in the website.

## CONTENT



## MEDIA



## ACKNOWLEDGEMENTS

* Thankyou to fellow SLACK user Michael Dijk for the suggestion on using www.responsinator.com to test the responsiveness of the site and help decide what 
viewing formats to virtually test the site on.

