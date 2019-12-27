# Destination Planner - My Second Milestone Project

The web page I have created is a Google Maps API. It is a holiday destination planner. As we all know choosing a new city to visit or plan a holiday in can be a daunting task. 
Most families only get to do this once a year so the right decision must be made on picking the right location.
Picking the right area is half the battle but getting as much information on that area is vital to a successful holiday and keeps everybody happy and interested.<br>
The user here can therefore, pick or choose a city of their choice where they may possibly spend their next vacation. 
The web page is compact, concise and gives the user three options they require to gain knowledge of for that individual city. 
They can then make an informed decision on choosing their next holiday destination.
The three options included are, Accommodation, Bars/Restaurants and Tourist Attractions as their points of interest.

## UX

Firstly, I would like to direct you to the UX directory above where you will find the Strategy, Scope, Structure and Skeleton (wireframes).

This web page is for any user who would like a vibrant, interactive page to decide on which city they would like to visit or explore on their next holiday. 
The web page is informative and straight to the point and the layout I feel gives the best view the user could hope for.<br> The layout
is such where every option you can choose is readily accessible. The functional area on the left I have used an autocomplete text box to search for a city name, which displays each and every city. You just
enter a city name where prompted and the autocomplete function will give you various cities that are available, depending on which letter you chose to start your search with.<br>
We then have three points of interest to choose from and are all labelled, including a reset button, which will take you back to the start to search again.
I've made the map as big as possible, so when the map populates with search results they are easily viewable on every screen size.
<ul><li>If a user wants to find out more information about a search result, from the drop-down results list, they click on the result they require and the information will show up with a location tag on the map.</li></ul>

## Features

The web page itself is a simple layout and it is more or less self explanatory from looking at your options within the page.
<ul><li>We start with a clearly marked heading which says Choose City. Underneath here we have an autocomplete search box. 
The user chooses the city of their choice which allows them then to choose from the points of interest they require the information for.</li>
<li>Within the points of interest area the user can click on one of three buttons, each a different points of interest.</li>
<li>Once the user chooses their points of interest they get a drop-down list of results, which then populates the map with different location tags which are lettered and which house 
the information they require.</li>
<li>The user then matches the letter on the results list to the map and then they click on the location tag within the map. Doing this
returns the name address telephone number and website of the chosen result.</li>
<li>Once the user has exhausted all results available they can choose the Start Over button to restart the process and go ahead and choose another city to see results for their next choice of city.</li></ul>

#### Future plans include:
<ul><li>The addition of further points of interest.</li></ul>

## Technologies Used 

<ul><li>HTML5 was used as the markup language for the site.</li><li>CSS3 was used to style the website</li><li> Bootstrap 3.3.7 for the main layout, along with Flexbox</li>
<li>Google Fonts was used for different text/fonts required</li><li>Cloud9 was used as the IDE to write the markup and css in an open source work-space</li><li>Git & Github were used to commit repositories to, again so the code can be viewed or edited or stored. It was also used to deploy the website.</li></ul>

#### The list of frameworks, languages & libraries used were: 

HTML: https://www.w3schools.com/ <br> CSS: https://www.w3schools.com/css/ <br> Bootstrap: https://getbootstrap.com/ <br> Google Fonts: https://fonts.google.com/
<br> Cloud9: https://aws.amazon.com/cloud9/ <br> Git: https://git-scm.com/ <br> Github: https://github.com/ <br> Google Maps Javascript API: https://developers.google.com/maps/documentation/javascript/examples/places-autocomplete-hotelsearch 


Finally, a lot of hours researching on Google were required also, but https://www.w3schools.com/ https://css-tricks.com/ & https://www.youtube.com/ were also a huge help with their tuition too.

## Testing

Each area of the site has been tested & appears to be working well. The user should be able to achieve their goal as the site intends, depending on whatever they choose to do when they visit. I have used Dev tools 
in Google Chrome to test the responsiveness of the site on different devices small and large and the site appears to render well on different screen sizes.<br>
In the autocomplete autofill area, if you type a letter into the search box you receive a list of cities beginning with, whether you type the first letter of the name of a city, or even for example, the first three letters like Dub - the results that are returned are Dublin, Dubai, Dubrovnik.
Then you click on or scroll down with the arrow keys to the city of your choice.<br>
When a result is chosen it is highlighted on the map and it shows the relevant information you requested for that specific place. If you click on the location tag within the map it shows up the information for that place.<br>
After choosing your city each button works as it should, each points of interest button with labels of Accommodation, Bars/Restaurants & Tourist Attractions when pressed takes you to the populated map.<br>
Once the Start Over button is clicked it restarts the whole search process for the next city, it also clears the results area, the map & it's location tags.<br>

Furthermore, I have used W3C Code Validator https://validator.w3.org/nu/ to verify there are no errors in my HTML and CSS. I have tried to keep the code as semantic as possible too.
I have yet to test the site out on any other browser other than Google Chrome and Android, so it has not been tested on Edge, Safari or IOS.

## Deployment 

I deployed the project using Github pages and the link to the website is: https://bren08.github.io/destination-planner-milestone-project-2/ <br>

I built the web page with a view to give the end user the best possible user experience. I made the map as big as possible without compromising on the functional area where the Points of Interest are located.<br>
The buttons are well highlighted and easily navigated and I also wanted to distinguish between the Points of Interest buttons and the Start Over button, so there is no confusion for the end user as to what button does what.<br>
A return button was added to the bottom of the page for mobile viewports to return to the Points of Interest area as the scroll function is required on mobile devices. This function returns the user to the top of the page without scrolling, if that is what their preference is.

## Credits

#### Contents:

The map was taken from Google Maps Javascript API: https://developers.google.com/maps/documentation/javascript/examples/places-autocomplete-hotelsearch

## Acknowledgements:

I would like to thank the good members of Code Institute Slack channel for their help and advice and finally my tutors & my mentor who steered me in the right direction.