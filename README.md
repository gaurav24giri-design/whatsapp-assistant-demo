# WhatsApp Assistant Demo

A chat demo of an assistant for small businesses. Customers ask questions, order, book and check on their order in a WhatsApp-style chat. The owner sees a live feed of bookings, orders and anything that needs a person.

**Live demo:** (add your link here)

This is a demo of the idea. It runs entirely in your browser with scripted replies. It is not connected to WhatsApp and does not use AI.

## Try it

Pick one of three sample businesses at the top: a bakery, a salon or a clothing store. Then try:

- Track an order: `#1042` or `#1043` (bakery), `#2001` or `#2002` (clothing store)
- Place an order, then track it with its new order number
- Book a table, appointment or styling session, then change or cancel it
- Write in Hinglish: `kal 7 baje table book karni hai`, `mujhe ek kurta chahiye`
- Ask for a refund to see a hand-off to the owner
- Press **Reset chat** to start over

## What it shows

- **FAQs:** delivery, payment, opening hours, returns and more, answered from each business's details
- **Order status and new orders:** with delivery fees that follow each shop's rules
- **Bookings:** opening hours, closed days, and a 2 hour notice rule are checked
- **Change and cancel:** the latest booking can be moved or cancelled
- **English and Hinglish:** replies follow the language the customer writes in
- **Owner panel:** bookings, orders, hand-offs and an estimate of time saved

## How it is built

A single `index.html` file with plain HTML, CSS and JavaScript. No framework, no build step, no server, and nothing is stored or sent anywhere. Open the file in a browser and it works.

The replies are scripted: keyword matching for the questions, and simple step-by-step flows for orders and bookings. A real version would use an AI model so customers could write anything, and would connect to the WhatsApp Business API.

## Make it your own

The three businesses are defined in the `BIZ` object near the top of the script in `index.html`. Change the name, hours, menu or price list, FAQs and booking rules to fit a different business.

## Run it

Open `index.html` in any browser, or host it on Cloudflare Pages or GitHub Pages.
