<img src="./assets/images/banner.jpg" width="320px">

To run a frontend (HTML, CSS, Javascript only) application in Gitpod, in the terminal, type:

python3 -m http.server

To run the webpage click on this link: https://inotila.github.io/AlchemistTours--MileStone1-/index.html ) 

<img src="./assets/images/responsive.jpg" width="320px">

# Alchemist Tours (Portfolio 1)

This project is for my final submision for my first milestone. The aim of the project is to code and deploy a static website using HTML and CSS. 

The last update to this file was: **October 26, 2021**

## About Alchemist Tours website

Alchemist Tours is a website for a company that offers shuttle services to and from Windhoek International airport as well as around the city of Windhoek. In order to market themselves they have created a website that lets people know about their serives and also offer them an opportunity to book a shuttle online. In addition, the website also promotes travel to the country so as to grow the tourism industry. Users of the are as ealry people who will be traveling to Windhoek Namibia( the countries only international airport) and will be indeed of transport to or from the airport as it is 60kms away from the City and one can not hitch a taxi from there. In addition, users are people considering travleing to Namibia and would like to know more about what the country has to offer.

The site owner, is a shuttle compnay. The company would like to make offer potential clients an opportunity to book their services online. Furthermore, provide market tourim in Namibia and provide rialble information about the country.

## Value

This site is for the conviences of booking transport for toursit in and around the Windhoek. Furthermore, this site is provide  prospective travelers with info about Namibia and give them a look (via the gallery) at what beautys Namibia has to offer. The webisite aims at marketing the country, so as to boost the toursim industry. 

## Potential features 

1. A forum to book a shuttle to or from the airport.
2. A gallery with pictures and videos of Namibia.
3. A page with factual infomation about Namibia
4. A link to flight booking sites

## Features
1. Welcome/home page -

<img src="./assets/images/pagehome.jpg" width="320px">
Introduces the company and it's servises. In addition, it gives users the opportunity to navigate various  to various pages on the website. This is opportunity is via the three circles. Users are alerted that the element is a link because if one hovers over them, the element expands to show its affordance.

The welcoming page is useful to the user becuase, introdures the users to what the webpage is about and an indication of what can be done on the page. Furthermore, users can jump to otherpages using the links.

2. booking form - 

<img src="./assets/images/pageforum.jpg" width="320px">

This is a form that allows users to book a shuttle. The form takes the details about the users name, their pickup/dropoff location and date, it also takes the number of passengers, and the users email. In addition there is a text field for additional request. While the text field is not required, the rest of the form inputs are required, their for should be filled out. There is also a button to submit the form. The button has is reponsive when hovered over, turning green when hovered over to indicate that is indeed a button.

The form is useful to the user becuase, its an easy way to book a shuttle.

3. about namibia - 

<img src="./assets/images/pageabout.jpg" width="320px">

A page that has information about Namibia. Users also have links to trip advisor and the gallery. These words are in bold to indicate that they are link. The trip advisor link opens on a new tab.

The about Namibia page is useful to the user becuase, here they can get basic info about Namibia if they are still deciding on whether they should travel to Namibia. In addition it links users to visual content(the gallery) and to other possible attractions in the country(trip advisor page).


4. gallery -

<img src="./assets/images/pagegallery.jpg" width="320px">

 An organized gallery with various high quality images.

 The gallery is useful to the user becuase,of visual content that shows users what to expect. In addtion it is a great marketing tool for those who are scouting for a holiday destination.

5. Nav - 

<img src="./assets/images/pageheader.jpg" width="320px">

a responsive navigation menu that indicates its current page by highlighting the current page. Furthermore, when hovered over underlines the link so that users understand that the words is a link.

The navigation menu is usefull to users because it shows users which page they are on by highlighting the active page. Futhermore, its and easy way to navigate the page. In general, it directs the user. It also shows the name of the company, so users know which company they are workinf with.

6. Footer -

<img src="./assets/images/pagefooter.jpg" width="320px">

we have footer to keep social media links and other ways to reach the company. These links are links that open in new tabs so as to not take the user away from the website.

The social media links are useful for the users because they encourage the user to get incontact with the company on other platforms(Facebook, Twitter, Instagram and Youtube). This gives them the ability to interact/contact the company and also research them more.


## Future Features
1. A link to flight booking sites
2. A live currecny indicator using APIs



## Testing
I test if this page works in different browsers.

I ensured that the project is reponsive, and the deisign looks good by using a minimalist approach. In addition I used the devtools to confirm that all sizes look good.

I ensured that the page is readable, and that it is easy to understand the page and the actions that are afforded to the user.

I have confirmed that all my inputs and fields work and accept the correct data format.

## Bugs and fixes
I didn't come across too many bugs as the page is solely HTML and CSS. The bugs I came across where links that didn't work because I had a syntax error. Other common bugs were images not loading on other devices because my file path was wrong. I failed to include the (.) to indicate that it document was being loaded from the current file path.

While testing I had feedback that the submit button lead particpants to an error page. They didn't not enjoy this even if they were just testing. So to fix this I put the button into an anchor element that lead to an thank you page. However,this didn't work no matter what I tried. the error that kept showing up indicated that the form is a post and so command was not being accepted. So my solution was to change the form method from post to get. While this is not what the form is for, it improved the testing process.

I had issues with the navigation menu when the screen went lower than 950px and lower. It would not align properly,so to fix this I changed the float for element from float right to float left. This made it look better.

## Unfixed bugs
No unfixed bugs

## Validator testing
Html -no errors returned from the official w3c validator

CSS -no errors returned from the official (jigsaw) validator

Accesibility -Conofimation that the colors and fonts used are easy to read and are accessible  by running it throught lighthouse in devtools.

## Deployment
This project has been deployed on Github pages. The link to project is ( https://inotila.github.io/AlchemistTours--MileStone1-/index.html ) 

## Reference 
This work is the orignal work of Inotila Nghaamwa, however the following resources were used to supplement:

I used a similar code the love running project for the Navigation bar and the footer. And generally I used the coding practices I learnt during my course to create this project. https://learn.codeinstitute.net/dashboard

I researched from https://developer.mozilla.org/en-US/ to help me create this project. 

My friend Brav Regimus contributed to this project by advising me to use felx to fix my issue with having the fotter not stick to the bottom.

I researched how to excute ceterain codes on stack overflow to set up my banner to be animated. Futhermore, I used discussions on layouts to guide me to bettering my layout. https://stackoverflow.com/

All images used are the property of Inotila and are marked with a logo at the bottom right corner.

## Credits 

Content -
Text- Research by Inotila Nghaamwa from https://en.wikipedia.org/wiki/Namibia

Images - All images used are the property of Inotila Nghaamwa and are marked with a logo at the bottom right corner.
