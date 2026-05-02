# RHINOS Shopify Theme

## Overview

RHINOS is an old-school bodybuilding apparel brand inspired by the golden era of bodybuilding (1970s–1980s).

This Shopify theme must reflect:
- strength
- discipline
- authenticity
- vintage gym culture
- premium athletic identity

The visual direction is heavily inspired by:
- Gold’s Gym
- classic American gym aesthetics
- vintage bodybuilding magazines
- varsity typography
- retro athleticwear
- old-school powerlifting culture

This repository contains the complete Shopify theme used for the RHINOS eCommerce store.

---

# Core Brand Identity

## Brand Values

- Strength
- Consistency
- Discipline
- Brotherhood
- Effort
- Legacy

RHINOS is not a generic fitness brand.
The experience must feel:
- bold
- timeless
- masculine
- premium
- authentic

Avoid modern “tech startup fitness” aesthetics.

---

# Design Direction

## Visual Style

The design language should feel:
- retro
- strong
- clean
- athletic
- editorial
- vintage

The website should resemble:
- classic bodybuilding magazines
- old gym posters
- old American gym merchandising
- vintage sportswear catalogs

---

# Typography

Primary typography inspiration:
- Varsity / collegiate fonts
- Bold condensed athletic typography
- Vintage sports lettering

Typography should feel:
- powerful
- readable
- iconic

Avoid:
- futuristic fonts
- minimal tech fonts
- ultra-modern startup styles

---

# Color Palette

## Primary Colors

- Vintage yellow
- Cream
- Navy blue
- Washed black
- Heather grey
- Burgundy accents

## Visual Intent

Colors should feel:
- worn
- timeless
- old-school
- premium

Avoid:
- neon gradients
- cyberpunk palettes
- excessive saturation
- glossy modern UI colors

---

# User Experience Goals

## Main UX Priorities

1. Mobile-first
2. Fast loading
3. Strong branding
4. High conversion
5. Clean navigation
6. Product-focused layout
7. Minimal friction

The user should immediately understand:
- this is a serious bodybuilding brand
- products are premium
- the brand has identity

---

# Technical Philosophy

## General Rules

- Keep code clean and modular
- Reuse components when possible
- Avoid duplicated CSS/JS
- Prioritize maintainability
- Avoid unnecessary dependencies
- Minimize external apps
- Optimize for performance
- Maintain Shopify best practices

---

# IMPORTANT DEVELOPMENT RULES

## DO NOT

- Break existing functionality
- Modify checkout logic
- Add unnecessary JavaScript
- Add large dependencies
- Use bloated animations
- Create duplicated sections/snippets
- Hardcode values when settings are preferable
- Reduce performance for aesthetics

---

# Performance Rules

Performance is a priority.

## Always optimize:

- image sizes
- lazy loading
- CSS duplication
- JavaScript execution
- render blocking assets

Avoid:
- unnecessary sliders
- excessive animations
- oversized libraries
- autoplay heavy media

---

# Responsive Rules

The entire experience must work perfectly on:
- mobile
- tablet
- desktop

Priority order:
1. Mobile
2. Desktop
3. Tablet

Spacing and typography must scale properly.

---

# Shopify Architecture

## Main Folders

### `/assets`
CSS, JS, fonts, images and theme assets.

### `/sections`
Main Shopify dynamic sections.

### `/snippets`
Reusable Liquid components.

### `/templates`
Page templates.

### `/layout`
Global theme structure.

### `/config`
Theme settings and schema configuration.

---

# Coding Standards

## Liquid

- Keep logic simple
- Use reusable snippets
- Avoid deeply nested conditions
- Comment complex logic

## CSS

Preferred approach:
- modular
- scalable
- reusable

Avoid:
- inline styles
- duplicated utilities
- unnecessary specificity wars

## JavaScript

Use JavaScript only when necessary.

Priority:
- lightweight
- readable
- performant

Avoid:
- large frameworks
- unnecessary DOM manipulation
- excessive event listeners

---

# Naming Conventions

## Sections

```text
product-card.liquid
hero-banner.liquid
collection-grid.liquid
