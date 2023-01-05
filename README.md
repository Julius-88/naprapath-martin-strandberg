# Naprapath Martin Strandberg

- Naprapath Martin Strandberg has created a business who's aim it is to treat, educate and help prevent injuries to all people so that they can live a healthier life. 

- The goal of this website is to attract a younger generation of people while 
    being accessible to everyone.
    
- They will be able to find information about their particular injury, the  treatments offered, general information about the business and be able to book a session or contact the owner.

![Image showing the website is responsive](./documentation/responsive-naprapath.jpg)

## Existing Features

- Navigation Bar
    - Featured on top of the website is the navigation bar. On the left corner the viewer can see the company name and logo and on the right corner they can see the various pages available.
    - Clicking on the company name and logo will bring them back to the landing page.
    - On the right side they can see which page they are on by it having a different background-color, border and having a bigger padding.
    - Hovering over the website pages will make them bigger and create a similar effect as the active page they are on.
    - The navigation bar is clearly displayed and makes the different sections easy to find. It is available on each page.

![navigation bar](./documentation/readme-navigation-bar.jpg)

## The Header Section

- The hero image
    - It has a zoom in animation to catch the eye of the viewer.
    - It displays a text related to the page they are on.
    - It contains a button that allows the viewer to book a session. Upon hovering it will change color to a darker green.
    - It contains a number to the owner the viewer can call to ask questions or to book a session. Upon hovering it will turn green and get an underline.
    - This section tells the user which page they are on and allows them to quickly book a session.

### Hero Image on Landing page

![Hero img on landing page ](./documentation/readme-hero-img-landing.jpg)

### Hero Image on Symptom page

![Hero img on symptom page](./documentation/readme-hero-img-symptom.jpg)

### Hero Image on Treatment page

![Hero img on treatment page](./documentation/readme-hero-img-treatment.jpg)

### Hero Image on Contact page

![Hero img on contact page](./documentation/readme-hero-img-contact.jpg)

## Landing Page

### About Me Section

- Introduces the viewer to the owner Martin Strandberg. They are given some information about him. This creates a familiarity with him and shows that he can be trusted since he has been in the business for a long time.

- There is also a button that allows the viewer to book a session. Upon hovering it will change color to a darker green.

![About Me Section](./documentation/readme-aboutme.jpg)

### Partner Section

- Showcases all the logos of the different companies he has a working relationship with. Re-establishing his expertice by having so many companies working with him. Thereby reinforcing trust with the viewer that he knows what he is doing.

![Partner Section](./documentation/readme-partners.jpg)

### Symptom Section

- Informs the viewer of the common misconception of how injuries develops and how he will go about treating them. This gives the viewer a general idea of how he works and what to expect. And reinforces a level of trust.

- There is also a button that will take the viewer to the symptoms page, where they can learn more about their symptom. The button upon hovering will turn a darker shade of green.

![Symptom Section](./documentation/readme-symptom-section.jpg)

## The Footer Section

- The footer holds all important general information for the user about the company.

- It shows the opening hours, the contact information and the address for visiting. 

- It also holds a button that takes the user to the contact page where they can ask a question. Upon hovering on the button it will turn a darker shade of green.

- Upon hovering on the email address and the phone number they will turn light green and get an underline.

- Email link
    - If clicked on will open the viewer's email provider so that they can send a message to the owner.

- Phone link
    - If clicked upon will prompt you to call the owner.

- It also informs that the page is copyrighted and whom has created it. The footer section is available on every page.

![Footer Section](./documentation/readme-footer-section.jpg)

## Symptom Page

- Contains information about the various symptoms people have, what the signs are and how the body reacts. Upon clicking on each title a descriptive text will appear underneath it.

- This let's the user understand more about their situation. Thereby being able to properly talk about their problem to the owner.

- Also contains a small information about the first visit at the end of the page. So the viewer knows what to expect.

![Symptom Page](./documentation/readme-symptom-page.jpg)

## Treatment Page

- In a similar style to the symptom page, it provides information about which treatment options he offers and what ailments they are used upon. 

- It allows the viewer to know what they should expect during the treatments and what he is capable off.

![Treatment Page](./documentation/readme-treatment-page.jpg)

## Contact Page

- Provides the user with a way to send a query to the owner. They will have to provide their full name, email address and phone number. 

- The send button turns a dark green upon hovering. 

- Upon completion the user will be taken to a customized respons page. Where they will be informed that this is not a real form but how they can get into contact with the owner. 

- It contains his email address, phone number, the book button and a return to landing page button. Each will react the same way as previously stated while hovering.

![Contact Form](./documentation/readme-contact-form.jpg)
![Respons Page](./documentation/readme-response-page.jpg)

## Additional Features & Ideas

- I was considering to add a book button at the end of symptom and treatment page to allow the viewer to easier book a session. 

- I was considering to change the information section of the symptom and treatment page to be in the shape of cards and stand side by side instead of underneath each other. I think this will provide a better user experience. 

- After having checked in Lighthouse it would seem the pictures I have used are too big and slows down the page. I would like to fix these.

- Add the owners social media accounts in the footer section.

## Testing

- Responsivity was tested through DevTools on Google Chrome.
    - For mobile version flex-direction column was used to make it easier to read.
- I have confirmed that it works on Google Chrome, Firefox and android phone.
- The form has been tested and requires entries in every field.

- Upon checking with Lighthouse it would seem the images need to be adjusted. The images taken from the owners website are of low resolution.

- Images taken from [Pexel](https://www.pexels.com/sv-se/) seem to be too big. Have to find a way of fixing it without the picture becoming too pixelated. 

### Validator Testing

- HTML Validation was tested through [W3C](https://validator.w3.org/)
    - During my initial test it would seem I had combined a link and a button. This has been fixed. Here is a picture of the Error ![error](./documentation/html-validator-problem-one.JPG)
    - Upon testing the landing page I recieved this Error ![error](./documentation/html-validator-problem-two.JPG) it has been resolved now. I should have used h2 instead of figcaption.
    - Upon a third testing, no errors were returned.
- CSS Validation was tested through [W3C](https://jigsaw.w3.org/css-validator/#validate_by_input)
    - No errors were returned.<p>
    <a href="http://jigsaw.w3.org/css-validator/check/referer">
        <img style="border:0;width:88px;height:31px"
            src="http://jigsaw.w3.org/css-validator/images/vcss"
            alt="Valid CSS!" />
    </a>
</p>

- Accessibility was tested through Lighthouse in devtools. The only problem seems to be the images used are too big or too small. They need to be adjusted. 
    - Validation for mobile ![Lighthouse for Mobile version](./documentation/lighthouse-mobile-validation.JPG)
    - Validation for desktop ![Lighthouse for Desktop version](./documentation/lighthouse-desktop-validation.JPG)

## Unfixed Bugs



## Deployment

- Github was used to deploy the site. [Naprapath Martin Strandberg](https://julius-88.github.io/naprapath-martin-strandberg/)

## Credit

- The original site that the owner owns is this: [Martin Strandberg](http://www.naprapatmartinstrandberg.se/)
    - I used some of his text as a base and altered them. I used what information he had given about his treatments and filled out the rest using Wikipedia. 

- The animation effect on the hero image was taken from Love Running Project that was provided by Code Institute.

- All pictures was taken from the owners facebook page and [Pexels](https://www.pexels.com/sv-se/) and modified with [I Love IMG](https://www.iloveimg.com/)

