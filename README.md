# Checkout UX/UI · White Label

A white-label, 3-step checkout flow, designed and prototyped in code by **Ticiana Paura**.

🔗 **Live demo:** https://ticianapaura.github.io/checkout-ux-ui/

## The flow

1. **Method** – a grid of payment methods (card, bank transfers, wallets).
2. **Amount** – pick from saved cards in a carousel, with CVV validation.
3. **Confirmation** – payment summary with its transaction ID.

## Design decisions

- **White label:** the brand (name, logo, support email) lives in a single config file, so a new merchant only changes that.
- **Design tokens:** colors, type and spacing defined as CSS variables.
- **Accessibility:** focus moves to each screen's title when advancing, for keyboard and screen reader users.
- **Components:** stepper, method tiles, saved card, CVV field, tooltip, toast and segmented control.

## Stack

React · TypeScript · Vite · CSS Modules
