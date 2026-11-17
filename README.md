# Shopify Custom Theme Development

A customized Shopify storefront built using Shopify's Dawn theme as a foundation. This project focuses on theme customization, responsive design, dynamic cart functionality, and storefront performance optimization.

## Project Overview

The objective of this project was to explore Shopify theme development and enhance an existing storefront by building custom Liquid sections, interactive cart functionality, and performance improvements.

## Tech Stack

- Shopify Liquid
- HTML5
- CSS3
- JavaScript
- Shopify CLI
- Git & GitHub
- GitHub Actions

## Key Features

### 1. Custom Promotional Banner
- Built a customizable homepage promotional banner.
- Added editable heading, description, image, button, and color settings.
- Designed a responsive layout for desktop and mobile.
- Implemented image alt text and optimized image loading.

### 2. Dynamic Free-Shipping Progress Bar
- Displays progress toward the free-shipping threshold.
- Shows the remaining amount required for free shipping.
- Displays a success message when the threshold is reached.
- Allows merchants to configure the threshold through theme settings.
- Updates dynamically when cart quantities change.

### 3. Performance and SEO Optimization
- Converted the promotional banner image from PNG to WebP.
- Reduced image size from approximately 522 KB to 24.23 KB (around 95% reduction).
- Implemented responsive image delivery using `srcset`.
- Added eager loading and high fetch priority for the banner image.
- Improved image alt text and homepage meta description.

### 4. Continuous Integration
- Integrated GitHub Actions for automated checks.
- Configured Shopify Lighthouse CI.
- Added automated Shopify Theme Check.
- Verified successful execution of both workflows.

## Lighthouse Results

Latest recorded mobile Lighthouse scores on the Shopify development preview:

| Category | Score |
|---|---:|
| Performance | 53 |
| Accessibility | 93 |
| Best Practices | 92 |
| SEO | 69 |

*Note: Scores may vary between runs. Development preview indexing restrictions may affect SEO results.*

## Development Setup

### Prerequisites
- Node.js
- Git
- Shopify CLI
- Shopify development store

### Installation

Clone the repository:

```bash
git clone https://github.com/Niy-S/shopify-custom-theme.git
```

Navigate to the project:

```bash
cd shopify-custom-theme
```

Start the local development server:

```bash
shopify theme dev --store your-store.myshopify.com
```

Replace `your-store.myshopify.com` with your own Shopify store domain.

## Learning Outcomes

- Understanding Shopify Dawn theme architecture.
- Working with Liquid sections, snippets, and schema settings.
- Building responsive storefront components.
- Implementing dynamic cart functionality.
- Optimizing images and basic SEO.
- Using Git and GitHub for version control.
- Configuring automated CI workflows.

## Project Status

Core customization, cart functionality, performance optimization, and CI integration completed.

## Repository

[View Source Code on GitHub](https://github.com/Niy-S/shopify-custom-theme)