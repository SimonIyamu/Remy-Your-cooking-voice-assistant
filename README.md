# Remy

![image](https://github.com/SimonIyamu/hackzurich23/assets/28822566/abff99d4-f81b-4de9-910f-dd419ac672f7)


Watch our [demo](https://youtu.be/Ygs8dQEqntM)

_"Okay Chef, what's the next step?"_  
_"Okay Chef, I don't have curry. What can I use instead?"_  
_"Okay Chef, Done!"_ 

This app was built during HackZurich 2023 within less than 24h from idea to product.

## What it does
Remy is an LLM powered voice assistant for the kitchen. The user can simply tell Remy what they're cooking (per URL to an online recipe or prompt it with an idea for a dish), Remy will interactively talk the user through every step of the recipe, allowing hand-free interaction. Additionally, as the user gathers ingredients, Remy suggests Migros’ sustainable alternatives, weaving sustainability effortlessly into the kitchen routine. The user can choose the voice that the narrator uses (Default, Authentic, Gordon Ramsay).

![image](https://github.com/SimonIyamu/hackzurich23/assets/28822566/208bf09b-ad8f-4787-bae7-5a722cbc16db)

## How we built it
At the core, LLM powers our back-end, deftly processing recipes, extracting ingredients, and suggesting alternatives, while adeptly navigating user prompts. Voice interaction? We leaned into the Web Speech API for flawless speech-to-text conversion, and chose Eleven-Labs to breathe life into the text, translating it back to guiding voices. The facade you interact with is sculpted using React-JS, housed comfortably on Firebase. And that touch of sustainability? It’s data-driven, with a nod to Migro's comprehensive products dataset.

## Challenges we ran into
We often lost focus, wanting to do too much at once. Combining our work was challenging. Understanding and responding to natural speech, like knowing when to listen, was hard. Setting up the app for everyone to use gave us headaches. And figuring out the best way to handle recipe prompts took a lot of time and effort. Goal setting and delivering a specific result by a certain time proved to be a challenge.

## Accomplishments that we're proud of
Seeing our first Proof-of-Concept come alive within 24hours was a major win; it was proof our idea wasn't just a dream but could work in real life. We're incredibly proud of the originality of our concept. The way we divided tasks and maintained focus was spot-on. And bringing together everyone's contributions into one cohesive app is a feat we'll always cherish.

## What we learned
We learned the importance and understanding the goal that we are all working towards together.

## What's next for Remy
We're eager to improve it further and make it even better. Our goal is to reach more people and have our app used in kitchens and stores, everywhere.

---
## Getting Started with Create React App

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).
To learn React, check out the [React documentation](https://reactjs.org/).
