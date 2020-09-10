# TheYummiPizza

This is a Laravel-based web application for ordering pizzas and menu items.
It provides a tabbed category view, product listing with prices, quantity selection, and a shopping cart.

## Features
- 📂 Category-based menu navigation with icons
- 🛒 Add items to cart with dynamic quantity and total price calculation
- 💶 Prices formatted in Euro with two decimal precision
- 🔄 Real-time cart updates
- ⚠️ Error handling with Bootstrap alerts

## Tech Stack
- **Backend:** Laravel (Blade templates, PHP)
- **Frontend:** Bootstrap, Font Awesome, JavaScript/jQuery
- **Templating:** Blade for rendering categories and products

## Structure
- `@extends('layout')` → Uses a shared layout template
- Categories (`$cats`) are displayed as navigation tabs
- Items (`$fortabs`) are shown in tabbed content with price and quantity
- Cart displayed on the right with Bootstrap cards

## Usage
1. Browse categories and select items.
2. Choose desired quantity (0–10).
3. Add items to cart.
4. Review and proceed to checkout.
