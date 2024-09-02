# A React Portfolio Template for GitHub

Add your GitHub username once and all of your info will automatically be updated. Deploy to GitHub pages in a few simple steps.

## [Live Demo](https://yassinkaabi.github.io/react-portfolio/#/)

[Google PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/)

![page speed](/README_images/speed.PNG)

## Light And Dark Themes

![Hero Light](/README_images/hero.PNG)

![Hero Dark](/README_images/heroDark.PNG)

### Getting Started

1. [Create a repository from this template](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template)
2. [Clone your new repository](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository)
3. Make sure [Node](https://nodejs.org/en/) is installed
4. Open your project and install the dependencies

   ```bash
   npm install
   ```

5. Navigate to the src directory and open src/config.js
6. Add your GitHub username ([src/config.js](https://github.com/Yassinkaabi/react-portfolio/blob/main/src/config.js#L18) line 18)

   ```javascript
   /* START HERE
   ************************************************************** 
     Add your GitHub username (string - "YourUsername") below.
   */
   export const githubUsername = "Your GitHub username here";
   ```

7. Start the development server to view the results

   ```bash
   npm start
   ```

### Updating the Contact section

![Projects](/README_images/contact.PNG)

1. The contact form uses [Formspree](https://formspree.io/), create an account and add your endpoint URL ([src/config.js](https://github.com/Yassinkaabi/react-portfolio/blob/main/src/config.js#L138) line 138)

   ```javascript
   /* Contact Info
   ************************************************************** 
     Add your formspree endpoint below.
     https://formspree.io/
   */
   export const formspreeUrl = "https://formspree.io/f/YourEndpoint";
   ```

### Deploy

A helpful guide for Create React App deployments with GitHub Pages can be found [here](https://create-react-app.dev/docs/deployment#github-pages).

1. Update the homepage value ([package.json](https://github.com/Yassinkaabi/react-portfolio/blob/main/package.json#L3) line 3)

   ```json
   "homepage": "https://YourUserName.github.io/your-repo/",
   ```

2. Run the deploy command

   ```bash
   npm run deploy
   ```

[Back to top :top:](#a-react-portfolio)