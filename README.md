# SleepOutside — WDD 330 team project (Team 11)

**SleepOutside** is an online shop for camping gear (tents, backpacks, sleeping bags and hammocks), built as the team project for WDD 330 (Web Frontend Development II) at BYU–Pathway Worldwide. It is vanilla JavaScript with ES modules, built with Vite.

This repository is my fork of the team repository, [olwalgeorge/wdd330-sleep-outside-team-11](https://github.com/olwalgeorge/wdd330-sleep-outside-team-11). I was a member of Team 11.

## Features

- **Product listing by category.** Products come from the course API (`https://wdd330-backend.onrender.com`) through `ExternalServices.mjs`, with search.
- **Product details**, with add to cart.
- **Cart**, kept in `localStorage`, with a running total.
- **Checkout.** `CheckoutProcess.mjs` works out the subtotal, tax, shipping and order total. It validates the form, sends the order to the API and shows the server's error messages, then opens a success page.
- **Shared header and footer** loaded from partials, and an `alertMessage()` helper for messages to the user.

[IMPLEMENTATION_SUMMARY.md](IMPLEMENTATION_SUMMARY.md) describes the week 4 checkout work step by step.

## Run it locally

```bash
npm install
npm run start      # Vite dev server
npm run build      # production build in dist/
npm run lint       # ESLint
npm run format     # Prettier
```

---

## From the course starter README

### BYU-Pathway Worldwide Online
#### WDD 330 - Web Frontend Development II

### ⛺ SleepOutside Starter Code

 - This repository is the start of the SleepOutside web application project for WDD 330. The repository contains branches which are checkpoints for the team and individual assignments throughout the course.

 - https://byui-cse.github.io/wdd330-ww-course/week01/team.html

### Prerequisites

- You must have Node installed to run the following commands.
[WDD 330 Setup Environment](https://byui-cse.github.io/wdd330-ww-course/intro/) 

### Common Workflow Commands

- `npm run lint` to run ESLint against your code to find errors.
- `npm run format` to run Prettier to automatically format your code.
- `npm run start` starts up a local server and updates on any JS or CSS/SCSS 
- `npm run build` to build final files when you are ready to turn in.


---
_BYU-Pathway Worldwide improves lives through access to spiritually based, online affordable higher education. Its mission is to develop disciples of Jesus Christ who are leaders in their homes, the Church, and their communities._



