# My Portfolio

## Description of Layout Approach

This webpage of My Portfolio utilizes a CSS Grid and Flexbox for layout management.

## Explanation of Responsive Design Techniques

Responsive design techniques are implemented using the media queries.

- A media query is defined for screens with a maximum width of 768 pixels. Within this media query, the navigation items are displayed as block elements instead of inline elements. This change allows for a more user-friendly vertical layout on smaller screens, making it easier for users to navigate the site on mobile devices.

@media (max-width: 768px) {
    nav ul li {
        display: block;
        margin: 10px 0;
    }
