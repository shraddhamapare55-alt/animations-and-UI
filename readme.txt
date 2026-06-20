Animations & UI Feedback - TuteDude Assignment

What I used
- HTML5
- Tailwind CSS (via CDN)
- A little bit of vanilla JS for the mobile menu toggle
- Custom @keyframes for the staggered fade-in animation

Sections I built

Section 1 - Built-in Animations
I used four of Tailwind's built-in animation classes here. animate-spin for a loading circle, animate-ping for a notification dot, animate-pulse for a skeleton loader, and animate-bounce for a bouncing dots effect. I had to use inline style for the bounce delays because Tailwind doesn't have delay utilities that work with animate-bounce directly.

Section 2 - Button Animations
Made seven buttons each showing a different hover effect. Things like scale, color change, rotate, lift (translate-y). The active:scale-95 one took me a second to figure out - you have to actually click the button to see it shrink slightly.

Section 3 - Card Animations
Three cards with hover effects. The second card uses the group and group-hover classes which I hadn't used before. You put group on the parent div and then group-hover: on the child element to control it from the parent hover.

Section 4 - Notification Badges
Three icons (bell, message, email) each with a small badge number and a different animation. Used relative and absolute positioning to place the badge on the top-right corner of the icon. The SVG icons are inline from heroicons.

Section 5 - Loading States
Three different loading patterns. A skeleton card with pulsing gray bars, a disabled button with a spinning icon inside it, and a bouncing dots loader with color delays.

Section 6 - Staggered Animations
Four cards that fade in from below with different delays (0ms, 150ms, 300ms, 450ms). I wrote a custom @keyframes called fadeup in a style tag and made four CSS classes with different animation-delay values. Used opacity:0 as default so the cards are invisible before the animation runs.
