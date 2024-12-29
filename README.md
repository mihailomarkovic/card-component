# Card Component

This repository contains my solution to the Stats Preview Card Component challenge from [Frontend Mentor](https://www.frontendmentor.io). The challenge was to create a responsive card component with a clean and visually appealing design that adapts seamlessly to different screen sizes.

## Overview

The purpose of this project was to practice building responsive layouts using **HTML** and **CSS** while maintaining a focus on semantic markup and design best practices. The card highlights key stats with bold, attention-grabbing visuals and an emphasis on accessibility.

## Links

- **Live Demo:** [Live Site](https://mihailomarkovic.github.io/card-component/)
- **Solution Repository:** [GitHub Repo](https://github.com/mihailomarkovic/card-component)

## Features

- Responsive design optimized for both mobile and desktop views.
- Clean and simple layout built with **Flexbox** and **CSS Grid**.
- Use of custom CSS properties to ensure consistency and scalability.

## What I Learned

This project reinforced my understanding of:

1. Creating responsive layouts using media queries.
2. Combining Flexbox and CSS Grid for efficient layout structuring.
3. Applying background overlays and filters to enhance images.

Here’s an example of one of the techniques I used for the image background:

```css
.img-box {
  background: linear-gradient(rgba(170, 92, 219, 0.6), rgba(170, 92, 219, 0.6)),
    url("./images/image-header-desktop.jpg");
  filter: contrast(200%) grayscale(20%) brightness(0.6);
  background-size: cover;
  background-position: center;
  border-radius: 0 11px 11px 0;
}
```
