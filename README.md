# MTM6201 Final - Plant Palette

**Figma Design Link:** https://www.figma.com/design/B1RO4noxSUfaXVYWg8Bqzr/Interactive-Prototype?node-id=0-1&t=FiHL8tTgfc7FGNDl-1
*Note: jarvisa@algonquincollege.com has been invited as an editor.*

## Interview Questions

**Tell us about your process:**
My process started with translating my high-fidelity UX prototype into a functional, mobile-first Bootstrap layout. I focused on semantic HTML first to ensure full accessibility (like skip links and proper heading hierarchies), then applied Bootstrap's grid system to handle responsiveness. Finally, I used CSS variables to override Bootstrap's default colours to match my specific Figma brand palette, and added custom media queries for pixel-perfect adjustments.

**Challenges you faced during development and how you overcame them:**
One challenge was ensuring the 4-column menu layout stacked properly on mobile devices without breaking the grid or stretching the images. I overcame this by implementing Bootstrap's `row-cols` utility classes to strictly define the column count per breakpoint, and used the `object-fit-cover` CSS property to keep the image aspect ratios perfectly clean.

**What have you learned by creating this project?**
I learned the importance of planning the HTML structure before writing any CSS. Mapping out the grid classes ahead of time based on my Figma designs made the actual coding process much faster. I also learned how critical grouped media queries are for keeping code maintainable (thanks to your feedback on my midterm!) and ensuring the site looks good on every screen size.

## Assets and Resources Used
* **Framework:** Bootstrap 5.3.3
* **Fonts:** Google Fonts (Open Sans)
* **Images:** [List the sources of your stock images here, e.g., Unsplash]
* *(If any AI images used)* **AI Images:** [Identify image and generator used, e.g., Hero image background generated via Midjourney]