# Frontend Mentor - Fylo data storage component

![Design preview for the Fylo data storage component coding challenge](./design/desktop-preview.jpg)

## Welcome! 👋

Thanks for checking out this front-end coding challenge.

[Frontend Mentor](https://www.frontendmentor.io) challenges allow you to improve your skills in a real-life workflow.

**To do this challenge, you need a basic understanding of HTML and CSS.**

## The challenge

Your challenge is to build out this data storage component and get it looking as close to the design as possible.

You can use any tools you like to help you complete the challenge. So if you've got something you'd like to practice, feel free to give it a go.

Your users should be able to:

- View the optimal layout for the site depending on their device's screen size

Want some support on the challenge? [Join our Slack community](https://www.frontendmentor.io/slack) and ask questions in the **#help** channel.

## Where to find everything

Your task is to build out the project to the designs inside the `/design` folder. You will find both a mobile and a desktop version of the design to work to. 

The designs are in JPG static format. This will mean that you'll need to use your best judgment for styles such as `font-size`, `padding` and `margin`. This should help train your eye to perceive differences in spacings and sizes.

If you would like the Sketch file in order to inspect the design in more detail it is available to buy from the challenge page on the platform.

You will find all the required assets in the `/images` folder. The assets are already optimized.

There is also a `style-guide.md` file, which contains the information you'll need, such as color palette and fonts.

## Building your project

Feel free to use any workflow that you feel comfortable with. Below is a suggested process, but do not feel like you need to follow these steps:

1. Initialize your project as a public repository on [GitHub](https://github.com/). This will make it easier to share your code with the community if you need some help. If you're not sure how to do this, [have a read through of this Try Git resource](https://try.github.io/).
2. Configure your repository to publish your code to a URL. This will also be useful if you need some help during a challenge as you can share the URL for your project with your repo URL. There are a number of ways to do this, but we recommend using [Vercel](https://bit.ly/fem-vercel). We've got more information about deploying your project with Vercel below.
3. Look through the designs to start planning out how you'll tackle the project. This step is crucial to help you think ahead for CSS classes that you could create to make reusable styles.
4. Before adding any styles, structure your content with HTML. Writing your HTML first can help focus your attention on creating well-structured content.
5. Write out the base styles for your project, including general content styles, such as `font-family` and `font-size`.
6. Start adding styles to the top of the page and work down. Only move on to the next section once you're happy you've completed the area you're working on.
7. If you'd like to try making your project fully responsive, we'd recommend checking out [Sizzy](https://bit.ly/fm-sizzy). It's a great browser that makes it easy to view your site across multiple devices.

## Deploying your project

As mentioned above, there are a number of ways to host your project for free. We recommend using [Vercel](https://bit.ly/fem-vercel) as it's an amazing service and extremely simple to get set up with. If you'd like to use Vercel, here are some steps to follow to get started:

1. [Sign up to Vercel](https://bit.ly/fem-vercel-signup) and go through the onboarding flow, ensuring your GitHub account is connected by using their [Vercel for GitHub](https://vercel.com/docs/v2/git-integrations/vercel-for-github) integration.
2. Connect your project to Vercel from the ["Import project" page](https://vercel.com/import), using the "From Git Repository" button and selecting the project you want to deploy.
3. Once connected, every time you `git push`, Vercel will create a new [deployment](https://vercel.com/docs/v2/platform/deployments) and the deployment URL will be shown on your [Dashboard](https://vercel.com/dashboard). You will also receive an email for each deployment with the URL.

## Sharing your solution

There are multiple places you can share your solution:

1. Submit it on the platform so that other users will see your solution on the site. Here's our ["Complete guide to submitting solutions"](https://medium.com/frontend-mentor/a-complete-guide-to-submitting-solutions-on-frontend-mentor-ac6384162248) to help you do that.
2. Share your solution page in the **#finished-projects** channel of the [Slack community](https://www.frontendmentor.io/slack).
3. Tweet [@frontendmentor](https://twitter.com/frontendmentor) and mention **@frontendmentor** including the repo and live URLs in the tweet. We'd love to take a look at what you've built and help share it around.

## Giving feedback

Feedback is always welcome, so if you have any to give on this challenge please email hi[at]frontendmentor[dot]io.

This challenge is completely free. Please share it with anyone who will find it useful for practice.

**Have fun building!** 🚀

## Community Sponsors

A massive thank you to our community sponsors!

- [Sizzy](https://bit.ly/fm-sizzy) is an extremely useful browser designed specifically to improve a developer's workflow when building websites. You can fire up multiple device emulators and run them all in sync while building out your web pages. Perfect for helping build fully responsive websites!
- [Diversify Tech](https://bit.ly/fem-diversify-tech) is an amazing resource for underrepresented people in tech. The site features job listings for anyone seeking new opportunities. The resource section is also full of useful links for you to dive into.
- [Dracula PRO](https://bit.ly/fem-dracula) is a beautiful dark theme to help keep you focused and productive while you code. The theme isn't just for your editor either. You can also apply it to your most-used apps like your terminal and even Slack!



<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <!-- displays site properly based on user's device -->

    <link
      rel="icon"
      type="image/png"
      sizes="32x32"
      href="./images/favicon-32x32.png"
    />
    <link
      href="https://fonts.googleapis.com/css2?family=Poppins&display=swap"
      rel="stylesheet"
    />
    <link rel="stylesheet" type="text/css" href="style.css" />

    <title>Frontend Mentor | Intro component with sign up form</title>
  </head>
  <body>
    <!-- 
  
   -->
    <div class="container">
      <div class="introduction">
        <h1>Learn to code by watching others</h1>
        <p>
          See how experienced developers solve problems in real-time. Watching
          scripted tutorials is great, but understanding how developers think is
          invaluable.
        </p>
      </div>

      <div class="registration">
        <div class="banner"><p><strong>Try it free 7 days</strong> then $20/mo. thereafter</p></div>
        <div class="form">
          <div class="input-form">
            <input type="text" placeholder="First Name" required>
            <p class="message">First Name cannot be empty</p>
          </div>
          <div class="input-form">
            <input type="text" placeholder="Last Name" required>
            <p class="message">Last Name cannot be empty</p>
          </div>
          <div class="input-form">
            <input type="email" placeholder="Email Address" required>
            <p class="message">Looks like this is not an email</p>
          </div>
          <div class="input-form">
            <input type="password" placeholder="Password" required>
            <p class="message">Password cannot be empty</p>
          </div>
          <button class="button">Claim your free trial </button>
          <div class="terms">By clicking the button, you are agreeing to our <strong>Terms and Services</strong></div>
        </div>
      </div>
    </div>
    <footer>
      <p class="attribution">
        Challenge by
        <a href="https://www.frontendmentor.io?ref=challenge" target="_blank"
          >Frontend Mentor</a
        >. Coded by <a href="#">Your Name Here</a>.
      </p>
    </footer>
  </body>
</html>


:root {
  --Red: hsl(0, 100%, 74%);
  --Green: hsl(154, 59%, 51%);
  --Blue: hsl(248, 32%, 49%);
  --Dark-Blue: hsl(249, 10%, 26%);
  --Grayish-Blue: hsl(246, 25%, 77%);
}

html,
body {
  margin: 0;
  height: 100%;
}

body {
  font-size: 16px;
  color: white;
  font-family: "Poppins", sans-serif;
  /* background-color: var(--Red); */
  background-color: var(--Dark-Blue);
  /* background-image: url("images/bg-intro-desktop.png"); */
  background-repeat: no-repeat;
  background-position: center;
  background-attachment: fixed;
  display: flex;
  flex-direction: column;
}

.container {
  display: inherit;
  flex: 1 0 auto;
  padding: 60px;
  border: 1px solid lawngreen;
}

.introduction {
  display: inherit;
  justify-content: center;
  align-items: center;
  flex-wrap: wrap;
  flex-direction: column;
  text-align: justify;
  padding: 55px;
  border: 2px dotted violet;
}

.introduction h1,
.introduction p {
  border: 1px solid cyan;
}

.registration {
  display: flex;
  flex-wrap: wrap;
  flex-direction: column;
  justify-content: center;
  padding: 40px;
  border: 1px solid orange;
}

.banner {
  display: inherit;
  align-items: center;
  border-radius: 15px;
  padding: 5px 100px;
  margin-top: 5em;
  margin-bottom: 20px;
  background-color: var(--Blue);
  box-shadow: 0px 10px 0px 0px rgba(22, 20, 20, 0.2);
  border: 1px solid red;
}

.form {
  display: flex;
  flex-direction: column;
  align-items: center;
  margin-top: 15px;
  background-color: white;
  border-radius: 15px;
  color: black;
  padding: 40px;
  box-shadow: 0px 10px 0px 0px rgba(22, 20, 20, 0.2);
  border: 2px dotted fuchsia;
}

.input-form{
    margin-bottom: 20px;
}

input {
  font-weight: 600;
  padding: 1.5em 2em;
  min-width: 400px;
  border-radius: 5px;
  border: 1px solid hsl(246, 25%, 77%);
  /* border: 3px solid chartreuse; */
}

.message {
  color: var(--Red);
  text-align: end;
  margin-bottom: 0;
  /* padding: 5px 15px; */
  font-size: 11px;
  font-style: italic;
}

.button {
  width: 100%;
  letter-spacing: 2px;
  text-transform: uppercase;
  border-radius: 5px;
  padding: 20px;
  border-style: none;
  outline: none;
  cursor: pointer;
  color: white;
  background-color: var(--Green);
  box-shadow: 0px 3px 0px 0px rgba(16, 150, 76, 1);
}

.terms {
  font-size: 11px;
  margin-top: 20px;
  color: var(--Grayish-Blue);
}

.terms strong {
  color: var(--Red);
  cursor: pointer;
}

footer {
  text-align: center;
  flex-shrink: 0;
  padding: 5px;
  background-color: rgba(185, 182, 211, 0.4);

  border: 1px solid blue;
}

.attribution a {
  text-decoration: none;
  color: var(--Dark-Blue);
}

.attribution a:hover {
  color: #ffce36;
}
