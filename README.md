SweetTreats Bakery Ordering Bot is a Python-based simulation of a WhatsApp-style chatbot that allows customers to place pickup orders for bakery items. This project demonstrates conversational flow, dynamic input handling, and basic state management without requiring an official WhatsApp API.
Absolutely! Here’s a polished **README** for your **SweetTreats Bakery Ordering Bot** project — ready to submit with your GitHub repository:

---

# SweetTreats Bakery — WhatsApp Ordering Simulation

## Overview

**SweetTreats Bakery Ordering Bot** is a Python-based simulation of a WhatsApp-style chatbot that allows customers to place pickup orders for bakery items. This project demonstrates conversational flow, dynamic input handling, and basic state management without requiring an official WhatsApp API.

It was created as part of the **SOFINDEX AI Automation Engineer Skills Assessment (Project 3)**.

---

## Features

* 👋 Personalized greeting and user name capture
* 🧁 Place multiple items in a single order
* 🔢 Quantity validation for each item
* 🕒 Pickup time scheduling
* 🧾 Order summary with confirmation step
* 🔄 Handles “No” responses by restarting the order process
* ✅ Simulated backend action when the order is confirmed
* ⚠️ Input validation to prevent blank or invalid entries

---

## How to Use

1. Clone the repository or download the script:

   ```bash
   git clone <repository-link>
   ```
2. Navigate to the project folder:

   ```bash
   cd sweet_treats_bakery
   ```
3. Run the bot using Python:

   ```bash
   python sweet_treats_bot.py
   ```
4. Follow the on-screen prompts:

   * Enter your name
   * Confirm if you want to place an order
   * Add one or multiple items and quantities
   * Set pickup time
   * Confirm your order

---

## Sample Conversation

```
👋 Hi! Welcome to SweetTreats Bakery.
What's your name?
> Numa

Welcome, Numa! Would you like to place an order for pickup? (yes/no)
> yes

What would you like to order?
> coke
How many coke(s) would you like?
> 2
Would you like to add another item? (yes/no)
> yes

What would you like to order?
> cake
How many cake(s) would you like?
> 1
Would you like to add another item? (yes/no)
> no

When would you like to pick up your order? (e.g., 4 PM)
> 5 PM

🧾 Order Summary:
  1. 2 x coke(s)
  2. 1 x cake(s)
Pickup Time: 5 PM

Is everything correct? (yes/no)
> yes

✅ Thank you, Numa! Your order has been confirmed for 5 PM. 🎉
Simulated backend action triggered: Order saved!
```

---

## Requirements

* Python 3.x
* No external libraries required

---
* Add pricing and calculate total cost for orders
* Integrate with Google Sheets or a real backend for order storage
* Add menu display with available items and emojis
* Add automated reminders for pickup

---



Do you want me to do that next?
