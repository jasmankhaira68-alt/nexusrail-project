# 🚆 NexusRail | Premium Transit SPA

**Live Demo:** [https://nexusrail.vercel.app](https://nexusrail.vercel.app)

## Overview
NexusRail is a high-performance Single Page Application (SPA) engineered to modernize the public transit booking experience. Built to eliminate the UI/UX friction and server-side lag of traditional railway portals, this platform shifts the computational load entirely to the client side.

## The Problem Statement
Current transit portals suffer from legacy architecture, leading to severe cognitive overload and latency during peak booking windows. NexusRail solves this by utilizing dynamic DOM manipulation and asynchronous state management to create a persistent, zero-refresh environment where users can search, verify, and book tickets instantly.

## Core Features
* **Zero-Refresh Navigation:** Instantaneous UI transitions powered by Vanilla ES6+ without traditional HTML page loads.
* **Asynchronous Grid Querying:** Custom Promise-based algorithms to simulate real-world network latency and data fetching.
* **State Management:** Secure booking generation and persistent passenger itineraries utilizing the Browser Object Model (`localStorage`).
* **Interactive UI:** Custom dynamic modal overlays for payment gateways and interactive vector mapping for spatial route selection.

## Tech Stack
* **HTML5** - Semantic structure and accessibility.
* **CSS3** - Custom properties (variables), Flexbox/Grid layouts, and keyframe animations (No external frameworks like Bootstrap/Tailwind).
* **Vanilla JavaScript (ES6+)** - Arrow functions, destructuring, higher-order array methods (`map`, `filter`, `reduce`), and Event Delegation.
