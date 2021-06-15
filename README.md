# for LOVE of CATS (fLoC)

for LOVE of CATS is a site for people who want to adopt a rescued cat. It enables people to browse through a list of cats that are available for adoption and gives information about each cat. It also allows people to send their contact information along with the cat they are interested in.
    
## Features

### Existing Features

#### Common Page features

- __Logo__
    - The logo is clickable and provides an easy way to navigate back to the home page.
    - It is consistently located on each page allowing the user to easily find it.
  
- __Navigation Bar__
    - Consistently located on each page allowing an intuitive user experience
    - Provides links to the Home, Selection, Adoption and Find Us pages
    - The active menu item is highlighted and themed according to it's target page

- __Hero images__
    - Each page contains a different hero image
    - Each hero image has a colour theme that matches the navigation bar item and the cover text
    - The hero images uses a zoom animation to draw the user into the page

- __Footer__
    - Pinned at the bottom of the page
    - Contains social media links for fast sharing or communication
    
#### Page specific features

- __Our Story page__
    - Provides information about who fLoC is, what they do and why they do it
    
- __Our Cats page__
    - Allows the user to see a list of cats available for adoption
    - Shows a photo, the cat's name and other useful information about cat
    - Updated when new cats become available and existing cats are adopted

- __Adoption request page__
    - Allows the user to submit a request to adopt a specific cat
    - The user supplies all required fields allowing fLoC to to establish contact and start the process
    
- __Find Us page__
    - Provides operating hours, adress and contact information

## Testing

### Layout

* Page title remains constant for all pages
* Logo location always remains constant
* Navigation bar location always remains constant
* Footer remains pinned to bottom of browser window
* Content pages header location remains constant on each page

### Navigation

* Clicking the logo navigates to landing page in the same tab
* Clicking the navigation menu items navigates to the correct site page in the same tab
* Clicking the social media links navigate to the correct external social media site in a new tab

### Form

* Input form validates required input fields and guides the user correctly to remedy the problem
* Submit button submits to the CI backend and displays information in a new tab

### UX

* Each page has a unique colour theme and the navigation hover and active page colour matches the target page's theme
* The selected navigation menu item background colour indicates which page is displayed

### Validator testing

- HTML
    - No html errors were returned for all four pages when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fcode-institute-org.github.io%2Flove-running-2.0%2Findex.html)
- CSS
    - One validation failure in the styles.css file reported by [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fvalidator.w3.org%2Fnu%2F%3Fdoc%3Dhttps%253A%252F%252Fcode-institute-org.github.io%252Flove-running-2.0%252Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en#css)
    - This issue will be fixed in the next release

### Unfixed Bugs

* See Validator testing error - Fixed in the next release
* Content on 'Our Cats' and 'I want one' is not dynamically centered - Fixed in next release
* Layout of cover text on hero images - Fixed in next release

## Deployment

- The site is deployed to GitHub pages. The steps to deploy were as follows:
    - In the fLoC GitHub repository, navigate to the Settings tab and select the Pages 
    - From the source section drop-down menu, select the Master Branch
- The live link can be found here - [https://morpheus-23.github.io/cat-love/](https://morpheus-23.github.io/cat-love/)

## Unimplemented assessment criteria

* Alt text equivalents to cater for the visually impaired
* Layout changes for all screen sizes

## Content

- All icons were taken from [Font Awesome](https://fontawesome.com/)
- All images were taken from [pixabay](https://pixabay.com/)
- Some design ideas were taken from Love Running and Coders Coffeehouse
- A lot of technical implementation information were taken from [W3Schools](www.w3schools.com)

## Directory structure

The site content is structured as follows:

| Directory | Description |
|---|---|
| / | html files  |
| /assets | non-html contet |
| /assets/css | all style sheets |
| /assets/images | all images |