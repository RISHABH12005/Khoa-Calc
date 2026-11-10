# Khoa

A lightweight, mobile-friendly market calculator for converting rupees and grams at a custom price per kilogram.

## Features
- English / Hindi interface switch
- Accepts English and Hindi numerals; numeric-only inputs
- Light and dark themes (theme preference is saved in the browser)
- Switch between rupees → grams and grams → rupees
- Editable price per kilogram and base weight
- Quick amount shortcuts and live reference prices
- Hindi market vocabulary guide for English speakers
- Responsive layout for phones, tablets, and desktop

## Run locally
Open `index.html` in any modern browser. No build tools, dependencies, or server are required.

## Formula
- Grams = Rupees × Base weight (grams) ÷ Price per kg
- Rupees = Grams × Price per kg ÷ Base weight (grams)

The default rate is ₹360 per 1,000 grams. Change it to match the shop's current rate.

## Deploy
Connect this repository to Vercel. Every push to the production branch will deploy the static site automatically.
