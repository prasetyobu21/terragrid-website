# TerraGrid Project Guidelines

## Project Overview
This project is a modern, minimalist website for a green energy company named **TerraGrid**.
*   **Framework:** Astro
*   **Styling:** Plain CSS (Scoped within Astro components) with a focus on modern, clean aesthetics.
*   **Animation:** GSAP (GreenSock Animation Platform) and ScrollTrigger are used extensively for complex, cinematic scroll-driven animations and transitions.
*   **Key Assets:** Reuses central visual assets (like `bg_image.png`) creatively across different sections (e.g., morphing backgrounds).

## Core Directives

### 1. Implementation Verification (Strict Rule)
**You MUST double-check to ensure that every implementation is fully complete, functional, and visually applied as intended BEFORE presenting it to the user.** 
*   Do not assume a CSS or GSAP change works just because the syntax is correct. 
*   Actively check for common pitfalls such as `z-index` layering issues, pointer-event blocking, or GSAP interpolation failures.
*   If a complex animation or layout change is requested, mentally simulate the rendering pipeline to guarantee it behaves as described in the reference or request.

### 2. Design Aesthetic
*   **Minimalism:** Prioritize readability, clean typography (e.g., negative letter-spacing for headlines), and ample whitespace.
*   **High-End Feel:** Use subtle, premium interactive states (e.g., backdrop blurs, soft expanding shadows, scale transforms on hover).
*   **Transitions:** Animations should feel tactile, smooth (`power2` or `cubic-bezier`), and deeply connected to user interaction (like scrolling).