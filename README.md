# Lopenve Limited

<p align="center">
  <img width="500" src="media/logo-blue.png" alt="Lopenve Limited Logo">
</p>

## Information about The Website

This website is a portfolio for Lopenve Limited, an engineer in the telecoms Industry.  This is the 2nd website I have made for a client, so this README lists some useful information about building the site, including the technologies and resources I used and any other details about the process that I might find useful in the future.

### File Structure

* index.html
* css
    * about-page.css
    * contact-page.css
    * footer.css
    * index.css
    * landing-page.css
    * navigation.css
    * sanitize.css
* scss
    * about-page.scss
    * contact-page.scss
    * footer.scss
    * landing-page.scss
    * navigation.scss
* media
    * photos for the website, including backgrounds, slideshow images and logos

### Technologies Used

**Sanitize css:**
This is a CSS reset I used to remove things such as the margin most browsers automatically add and other styles.  Their github writes "sanitize.css styles adhere to common developer expectations and preferences", for example, box sizing is equal to border box by default, which is not in the css specification but a common reset developers add before they write any css.
[Sanitize css](https://github.com/csstools/sanitize.css)

**Mailgo js:**
Mailgo is a neat modal that pops up when a user wants to use the email or phone link available on the website.  Rather than taking the user to the default email application on their device, which is usually not the email client they use, it gives the user multiple options to choose from, including gmail and outlook, the same goes for the phone contact as well.
[Mailgo js](https://mailgo.js.org/)
