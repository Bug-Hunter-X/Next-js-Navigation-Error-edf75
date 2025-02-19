# Next.js Navigation Bug

This repository demonstrates a common routing issue in Next.js applications.

## Problem

The application has two pages: 'Home' and 'About'.  The 'Home' page includes a link to navigate to the 'About' page.  However, clicking the link results in a routing error.

## Solution

The solution involves verifying the Next.js configuration and ensuring correct usage of the `<Link>` component for navigation.  Properly structured paths and file locations are crucial for successful navigation.

## How to Reproduce

1. Clone this repository.
2. Install dependencies: `npm install`
3. Run the development server: `npm run dev`
4. Observe the error when navigating to the '/about' page.