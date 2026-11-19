# SBA3 - Frontend Mentor Challenge

This is my solution for the **SBA3** challenge on Frontend Mentor. For this project, the goal was to take a Figma design and build it as accurately as possible using HTML, CSS, and Bootstrap. The focus was on matching the visual layout and making sure it looks good on different screen sizes, rather than building out complex features.

## Tools Used

* HTML5
* CSS3
* Bootstrap 5
* Git & GitHub

## How I Built It

First, I looked closely at the Figma file to check the spacing, colors, fonts, and overall layout. I kept my project folder simple by organizing my HTML, custom CSS, and images into separate files.

* **Layout:** I used Bootstrap’s grid system (`container`, `row`, and `col`) so the page adjusts properly on phones, tablets, and desktops.
* **Bootstrap Features:** I used Bootstrap utility classes for quick spacing and alignment, along with built-in components like **cards / buttons / navbar ** to speed up the build.
* **Custom CSS:** Because Bootstrap has a standard default look, I added a custom CSS file to match the exact colors, fonts, and small details from the Figma design so nothing looked off.

## Challenges & Fixes

The hardest part was getting Bootstrap’s default styles to match the exact measurements in Figma. Sometimes Bootstrap added extra padding or borders that threw off the spacing. Whenever that happened, I used the browser's inspect tool to find out what Bootstrap was doing, and then I adjusted it with utility classes or wrote a quick fix in my custom CSS.

## Reflection

Building this project was great practice for turning a design file into a real webpage. My biggest challenge was getting Bootstrap components to match the exact look of the Figma mockup. Since Bootstrap comes with its own default styles, getting colors, shadows, and spacing to line up took some patience.

To get around this, I let Bootstrap’s grid and utility classes handle the main layout and responsiveness, while using my own CSS file to fine-tune the colors, fonts, and exact spacing. Checking elements with browser dev tools really helped me spot where Bootstrap was adding extra margins so I could fix them easily.

If I had more time, I would spend extra effort polishing how the page looks on tablet screens between mobile and desktop sizes. I would also add some smooth hover effects to buttons and links to make the page feel a bit more interactive.
