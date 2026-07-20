# Boxchampy
Figma to Wordpress Elementor https://www.youtube.com/watch?v=rrd91OK9YYI&amp;t=168s


# Using Figma to Claude
# Connector Figma 
# Prompt Example
I will provide a Figma design link

<LINK> (Copy as link selection?)

Your task is to generate a complete, production-ready HTML file with embedded CSS (inside one <style> tag) and minimal JavaScript (inside one <script> tag) — all in the same file. Requirements:
1. The implementation must be pixel-perfect (1:1) compared to the Figma design.
2. Do not redesign, reinterpret, or improve anything. Reproduce exactly what is in Figma.
3. Use semantic HTML5 structure (header, nav, section, main, footer, etc.).
4. Do not use any frameworks (no Tailwind, no Bootstrap). Pure HTML, CSS, and minimal vanilla JavaScript only.
5. All CSS must be written manually inside one <style> tag.
6. The layout must be fully responsive:
    * Desktop (default styles)
    * Tablet (max-width: 1024px)
    * Mobile (max-width: 768px)
7. Use Flexbox and/or CSS Grid where appropriate.
8. Maintain exact:
    * spacing
    * font sizes
    * font weights
    * colors
    * border radius
    * shadows
    * line heights
9. Extract reusable design tokens into :root variables:
    * colors
    * font sizes
    * spacing
10. Use clean BEM methodology for class naming.
11. Images must use proper <img> tags with descriptive alt attributes.
12. Follow modern CSS best practices. Navbar Requirements:
* On desktop: standard horizontal navigation layout.
* On tablet and mobile (max-width: 1024px):
    * Replace navigation links with a hamburger button.
    * The hamburger must toggle the visibility of the navigation menu.
    * The menu must expand/collapse smoothly (CSS transition required).
    * Use minimal vanilla JavaScript for toggle functionality.
    * The menu must be accessible (aria-expanded, proper button element).
    * No external libraries.
1. Do not add features that are not present in the Figma design.
2. If spacing or font size is unclear, calculate proportionally from the design instead of guessing.
3. If something from the Figma link cannot be accessed, state what is missing before generating code.
4. Output only the final complete HTML file. No explanations.



