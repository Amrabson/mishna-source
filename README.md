# Nishmas Mishna — Daily Torah Learning Website

A single-page website for offering daily Torah learning in the merit of individuals, with integrated payment options, custom plan building, and enquiry forms.

## Overview

Nishmas Mishna is a static, client-side website designed to present and manage a Torah learning service. Users can:

- Select structured learning plans  
- Build custom daily learning combinations  
- Request specific sefarim  
- Submit general enquiries  
- Complete payments via PayPal (one-time or subscription)  

The site emphasizes clarity, simplicity, and a refined visual design aligned with its purpose.

## Features

### 1. Structured Learning Plans
- Multiple predefined tiers:
  - Mishnah a Day  
  - Mishnah + Tehillim  
  - Mishnah + Tehillim + Tomer Devorah  
  - Full Seder with Daf Gemara  
- Clear monthly pricing display  
- Toggle between:
  - One-time payment  
  - Recurring subscription (PayPal)  

### 2. PayPal Integration
- PayPal JavaScript SDK integration  
- Supports:
  - One-time payments via hosted links  
  - Subscription plans via `actions.subscription.create`  
- Lazy rendering of subscription buttons for performance  

### 3. Custom Learning Builder
- Users can select individual components:
  - Mishnah  
  - Kapitel Tehillim  
  - Perek Tomer Devorah  
  - Daf Gemara  
- Dynamic price calculation  
- Redirects to PayPal with computed amount  

### 4. Sefer Request Form
- Users can request custom learning (e.g. specific masechta or sefer)  
- Submitted via Formspree  
- Includes:
  - Name  
  - Email  
  - Requested sefer  
  - Optional Hebrew name and notes  

### 5. General Enquiry Form
- Captures:
  - Contact details  
  - Plan interest  
  - Learning dedication (kavana)  
  - Additional message  
- Async submission with success state handling  

### 6. Direct Contact Options
- WhatsApp deep link  
- Email link  
- Bank transfer note (manual handling)  

### 7. Fully Responsive Design
- Mobile-first layout  
- Adaptive grids and sections  
- Typography:
  - Inter  
  - Cormorant Garamond  

## Tech Stack

- HTML5  
- CSS3 (custom, no framework)  
- Vanilla JavaScript  
- PayPal JavaScript SDK  
- Formspree (form backend)  

No build tools or frameworks are required.

## Project Structure
/
└── index.html # Entire application (HTML, CSS, JS)


This is a fully self-contained static site.

