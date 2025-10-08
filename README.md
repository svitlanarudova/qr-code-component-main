![Frontend Mentor](https://img.shields.io/badge/Frontend%20Mentor-Challenge-4BC0F0?logo=frontendmentor&logoColor=white) ![#1](https://img.shields.io/badge/%231-red) [![Live Preview](https://img.shields.io/badge/Live-Preview-green)](https://твоя-ссылка-на-live-preview)



# Frontend Mentor - QR code component

![Design preview for the QR code component coding challenge](./preview.jpg)

## Project Overview 📋 

This is my solution to the QR code component challenge on Frontend Mentor.
The goal was to build a responsive component that matches the provided design as closely as possible, working well on both mobile and desktop devices.

## Built With 🛠️

-- Semantic HTML5 markup: main, article, footer

-- CSS Custom Properties (variables)

-- Flexbox and CSS Grid

-- Mobile-first workflow

-- Modern CSS logical properties (inline-size, block-size, margin-inline, etc.)

##  What I Learned💡

1. **CSS Custom Properties Organization**: I structured my CSS variables systematically for better maintainability
2. **Modern CSS Logical Properties**: Instead of traditional properties, I used logical properties for better internationalization support
3. **Accessibility Best Practices**:

   -- Added a visually-hidden h1 for proper document structure
   
   -- Used semantic HTML (main, article, footer)
   
   -- Provided descriptive alt text for the QR code image

   -- Ensured proper heading hierarchy (h1 → h2)

4. **Smart Hover Effect**: Implemented hover effects only for devices with hover capability
5. **Performance Optimization**: Added GPU acceleration for smoother animations
   

## Challenges I Faced 🚧

**Challenge 1:** CSS Variable Scoping

-- Problem: Initially defined CSS variables inside a specific element, making them unavailable globally

-- Solution: Moved all variables to :root for global accessibility

**Challenge 2:** Proper Document Structure

-- Problem: The card heading was the only h1 on the page, which isn't semantically correct

-- Solution: Added a hidden page-level h1 and changed the card heading to h2

##  Acknowledgments 🙏
Thanks to Frontend Mentor for providing this challenge and to the community for support and feedback

