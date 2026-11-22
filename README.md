# TrainMe

**Try it live: https://choonga25.github.io/TrainMe/**

Free, evidence-based personal training: answer a few questions and get a weekly workout plan, a Sydney-friendly meal plan with recipes and a shopping list, and a short YouTube demo for every exercise.

This is a prototype. It's one page (`index.html`) plus meal photos in `img/meals/`. There is no build step and no server.

## Notes
- Accounts are saved in each visitor's own browser, so they don't carry over between devices.
- **Email plan** lets people copy the plan into an email, open their email app, or download it. To send emails automatically, add EmailJS keys to `EMAILJS` near the top of the script in `index.html`.
- The AI coach only works when the page is opened on claude.ai, so it is hidden here.
- Food photos are from Unsplash.
