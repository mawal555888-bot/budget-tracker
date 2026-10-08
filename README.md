# SpendWise Dashboard Shell

## Overview

SpendWise is a responsive personal finance dashboard shell built using HTML and modern CSS layout techniques. The project provides the visual foundation for a future budgeting application using realistic static financial information.

## What I Built

The dashboard contains:

- A sidebar navigation menu
- A dashboard header
- A spending overview section
- Six financial category cards
- Food, Transport, Rent, Entertainment, Savings, and Utilities categories
- Responsive layouts for smaller screens
- Hover and keyboard-focus micro-interactions
- A dark theme using the user's system color preference

## Project Structure

### `index.html`

The HTML file provides the dashboard structure, including:

- Sidebar navigation
- Header and account information
- Spending overview
- Six category cards
- Static financial information

Each dashboard card uses `tabindex="0"` so it can receive keyboard focus.

### `style.css`

The stylesheet provides the complete visual layout and responsive behavior.

It uses:

- CSS Grid for the overall dashboard
- CSS Grid for the category card layout
- Flexbox for the sidebar
- Flexbox for the header
- Flexbox inside each dashboard card
- CSS custom properties for the color theme
- Responsive media queries below 768px
- Hover and focus animations
- A dark theme using `prefers-color-scheme: dark`

## Responsive Design

The dashboard uses a media query below 768px.

On smaller screens:

- The sidebar and main content use a single-column layout
- Navigation items become more flexible
- The header stacks vertically
- Category cards display in one column

The responsive layout can be tested using the browser DevTools Device Toolbar.

## Micro-interactions

Dashboard cards include subtle hover and keyboard-focus effects.

The interaction uses:

- `transform`
- `box-shadow`
- A 200ms transition

The animation applies to both mouse hover and keyboard focus.

## CSS Theme

The application defines its main colors using CSS custom properties inside `:root`.

The variables include:

- Brand color
- Accent color
- Surface color
- Background color
- Primary text color
- Secondary text color
- Border color

A dark theme overrides these variables when the user's system prefers dark mode.

## Technologies Used

- HTML5
- CSS3
- CSS Grid
- Flexbox
- CSS Custom Properties
- Responsive Media Queries

## Author

Mawal
