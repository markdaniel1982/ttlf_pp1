# Trip the Light Fantastic

Trip the Light Fantastic is a site for information about the digital record label run by 4 knowledgable and enthusiastic friends from the Midlands, UK. 
The site is aimed at followers and fans and will allow them to learn more about the owners by way of a DJ profile page, a gallery of latest track releases, and also to view and buy branded merchandise from an external webshop (webshop is embedded).

_____

## Features
The site lands on a page displaying the brand logo, a short 'about us' section and a gallery of the latest track releases from the label.

![header and navigation](/assets/images/header.png "Header and Navigation")

* Navigation and header

There is a hamburger menu which opens to display links to the pages contained within the site (DJ profiles & merch store). This is displayed across all 3 pages to allow for easier, more intuitive navigation.

The pages are responsive when viewed on smaller devices, where the content resized to fit the screen and improve viewability.

_____

## Testing
All pages have passed through an HTML validator any any errors have been corrected
Errors found:
* 1 unclosed dev element on Merch page. this was fixed and when the checker was run again, there were no errors

The css has also been passed through a validator and 1 error has been corrected
Errors found:
* Padding-left on the media query for smaller devices was not needed. this has been removed
___

### Errors & Debugging
While running the code through a validty checker, I had included a 'div' inside an 'h2' element on the profiles page. All instances were corrected and there are no longer any errors

In my css stylesheet, I had put the incorrect number in an rbga element for transparency. The value of 255 was corrected to 1

Throughout the project, I was checking the responsivity for smaller devices, debugging using devtools in Chrome and adjusting any elements accordingly. The main issue i had was the positioning of the hero text on the home page, which was sitting too low on smaller devices. This was fixed with a media query to reposition the element when viewed on a mobile phone.
_____

## Deployment

_____

## Credits

___
### Code

* Code for 'latest releases' grid found on [Codepen](https://codepen.io/TexV/pen/pwywNW) and amended to suit my needs
* Color gradient css code from [w3schools](https://www.w3schools.com/css/css3_gradients.asp) and amended to suit my needs

### Content & Media

* Content from the site, including logos and bio text has been taken from [ttlf.net](ttlf.net) (the brands' current live site) 
* Content and images from latest releases section on homepage has been taken from [toolbox digital shop](https://www.toolboxdigitalshop.com/trip-the-light-fantastic.html)
* Fonts from Google fonts
* Icons from Fontawesome