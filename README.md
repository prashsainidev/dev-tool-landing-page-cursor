# Cursor Landing Page Clone - Web Dev Cohort 2026

Hey everyone! This is my submission for the Chai Code Web Dev Cohort peer review assignment. I have recreated the desktop-first developer tool landing page inspired by the **Cursor website**, relying purely on HTML and CSS.

**Author:** Prashant Saini

## 📸 Final Output Screenshot

Here is the final rendering of my cloned page:

![Cursor Full Page Clone](./Cursor-The-AI-first-Code-Editor.png)

## 🎯 Learning & Approach

My primary objective here wasn't to add fancy interactives or JavaScript plugins, but to completely nail the visual architecture and CSS layout structure exactly as the instructor requested.

### Which Sections Were Recreated?
I successfully mapped out and built all 11 required sections from the assignment brief:
1. **Top Navigation Bar:** With proper links and carefully styled sign-in/download CTA buttons.
2. **Hero Section:** Features the massive bold heading and a custom CSS-crafted mock Editor window (mimicking macOS buttons and code syntax blocks).
3. **Trusted By / Logos:** Typography-based logos designed to mimic original SVG spacing and branding.
4. **Feature Sections:** Three distinct, alternating layout blocks featuring text on one side and a mock visual on the other.
5. **Feature Cards:** A 3-column flex/grid highlighting functionality.
6. **Testimonials:** Clean layout for user reviews and avatars.
7. **Use Cases / Stories:** Solid image-and-text card structure.
8. **Changelog / Updates:** Date-stamped minimal list layout.
9. **Team / About:** Spaced cleanly with a wide hero image layout.
10. **Final CTA:** Bold headline and large button setup at the bottom.
11. **Footer:** Split into a multi-column layout mimicking the complex actual Cursor site footer.

### 🎨 Design System & Styling (Fonts and Colors)
To keep the layout clean and visually accurate to the reference:
- **Fonts Used:** I implemented the `Inter` font stack (`font-family: 'Inter', -apple-system, sans-serif`) to specifically match Cursor's premium tech typography. 
- **Colors Used:**
  - **Backgrounds:** Set up a nice dark mode theme using `#0a0a0a` & `#080808` to give section depth without using flat blacks everywhere.
  - **Text:** Main headings use `#f4f4f5` (pure off-white) while paragraphs use `#a1a1aa` for comfortable readability.
  - **Borders & UI:** Very subtle accents using `#1a1a1a` and `#222` to outline cards cleanly, giving it a premium glass/dark vibe.

### Notes on Constraints Handled:
- I strictly followed all constraints: **100% vanilla HTML and CSS**. 
- **Zero JavaScript** and **Zero TailwindCSS** were used in this project.
- No flashy, unnecessary animations or effects—pure layout logic.
- Even though the assignment stated "desktop-only", I organically threw in some graceful CSS wrapper configurations (`max-width: 1200px`) and some extremely basic fallback media queries at the bottom of `style.css` so the grid doesn't visually break upon resizing, ensuring a smooth reviewing experience for peers.

Feel free to inspect the DOM and source code. Thanks for reviewing!
