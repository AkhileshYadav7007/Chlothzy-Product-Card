# Chlothzy-Product-Card
<!-- 
    Part 2: Technical Explanation

    1. Overall Approach & Goal:
    The goal was to create a responsive, accessible product card that allows users to switch between different color variations. The user sees real-time updates of the image and price upon selecting a swatch, enhancing UX and interaction.

    2. HTML Structure:
    - <section>: Container for the product card.
    - <figure>: For displaying the product image.
    - <h2>: Product title.
    - <p>: Price element.
    - <div class="swatches">: Contains the color swatches with role="radiogroup".
    - Each swatch is a div with role="radio" and aria-checked for accessibility.

    3. CSS Styling & Responsiveness:
    - Flexbox used for layout; media query ensures responsiveness.
    - Swatches are styled as colored circles.
    - Active swatch shows a visible border.
    - Transition effect added to image for smooth change.

    4. JavaScript Functionality:
    - Used an array of objects (productData) for different variations.
    - Event listeners handle click and keydown for accessibility.
    - Updates the image, price, and aria attributes dynamically.

    5. Accessibility:
    - Alt text for product images.
    - ARIA roles (radiogroup, radio, aria-checked) added.
    - Keyboard navigation supported via keydown event.

    6. Potential Challenges:
    - Image loading delays can be improved with preloading.
    - Unavailable colors can be greyed out in future.
    - Ensured tap events are responsive on mobile with proper size and spacing.
  -->
