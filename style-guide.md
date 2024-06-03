# Front-end Style Guide

## Layout

The designs were created to the following widths:

- Mobile: 375px
- Desktop: 1440px

## Colors

### Primary

- Pale blue: hsl(225, 100%, 94%)
- Bright blue: hsl(245, 75%, 52%)

### Neutral

- Very pale blue: hsl(225, 100%, 98%)
- Desaturated blue: hsl(224, 23%, 55%)
- Dark blue: hsl(223, 47%, 23%)

## Typography

### Body Copy

- Font size (paragraph): 16px

### Font

- Family: [Red Hat Display](https://fonts.google.com/specimen/Red+Hat+Display)
- Weights: 500, 700, 900
<div class="order-summary">
  <img src="music-image.png" alt="Music image">
  <div class="order-details">
    <h2>Order Summary</h2>
    <p>You can now listen to millions of songs, audiobooks, and podcasts any device anywhere you like!</p>
    <div class="plan-details">
      <h3>Annual Plan</h3>
      <p>$59.99/year</p>
    </div>
    <button>Proceed to Payment</button>
    <button>Cancel Order</button>
    <button>Change Order Summary</button>
  </div>
</div>
CSS:

css
Edit
Download
Copy code
.order-summary {
  display: flex;
  align-items: flex-start;
}

.order-summary img {
  width: 100px;
  height: 100px;
  margin-right: 20px;
}

.order-details {
  flex: 1;
}

.plan-details {
  margin-bottom: 20px;
}