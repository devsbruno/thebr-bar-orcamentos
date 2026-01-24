
# The BR Bar - Smart Quote Web App 🍸

> A Serverless Web App for order automation and lead qualification via WhatsApp for the premium bartending industry.

![Status](https://img.shields.io/badge/Status-Production-brightgreen) ![Tech](https://img.shields.io/badge/Tech-HTML5%20%7C%20JS%20%7C%20Geolocation-blue)

## 🎯 The Problem

The client (The BR Bar) was facing a bottleneck in their sales funnel: pre-qualifying leads via WhatsApp was manual, repetitive, and error-prone. Critical details like event location, date, and guest count were often lost in unstructured conversations.

## 🚀 The Solution

I engineered a responsive Web App that acts as a "Digital Pre-Sales Agent":

1. **Structured Data Collection:** Captures critical event details (Date, Guest Count, Event Type) before the conversation starts.
2. **Smart Geolocation (Reverse Geocoding):** Integrates with the Navigator API & OpenStreetMap to capture the user's exact GPS location and convert it into a readable address, optimizing logistics planning.
3. **Dynamic Package Logic:** Users select service tiers (Essential/Premium) and receive immediate visual feedback on the included cocktail menu.
4. **WhatsApp Deep Linking:** Generates a pre-formatted, encoded message that opens directly in the bartender's WhatsApp, containing a professional summary of the request.

## 🛠️ Tech Stack

- **Frontend:** HTML5, CSS3 (High-End/Responsive Design), Vanilla JavaScript.
- **APIs:** Navigator Geolocation API & OpenStreetMap (Nominatim) for coordinate-to-address conversion.
- **Deployment:** Vercel (CI/CD via GitHub).

## ✨ Key Features

- ✅ **Premium UX:** "Luxury" aesthetic designed for high conversion rates.
- ✅ **Dynamic Feedback:** Menu items update in real-time based on package selection.
- ✅ **Exception Handling:** Robust logic for dynamic inputs (e.g., "Other" event types) and GPS timeouts.
- ✅ **Zero Backend:** 100% client-side architecture (Zero Infrastructure Cost).

---

Developed by **Barusky Labs**
