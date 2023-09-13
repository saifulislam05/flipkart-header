# Flipkart Navbar Ass-7 CSS

## Hosted Link
You can view the project live at [View live Project](https://saifulislam05.github.io/flipkart-header/)

## Project Description
The "Flipkart" project is a web page that replicates the design of the Flipkart e-commerce platform's header section. It includes a navigation bar, search input, and various navigation links.
## HTML Explanation

### Header (`.header`)
![image](https://github.com/saifulislam05/flipkart-header/assets/73392705/ed3daeb1-f5d4-41a2-9d92-905cfcc182e0)

- The header contains the logo, search bar, and navigation links.
- The logo includes the Flipkart logo image and "Explore Plus" text with styling.
- The search bar allows users to input search queries.
- Navigation links include "Login," "Become a Seller," "More," and "Cart."

### Variety Section
![image](https://github.com/saifulislam05/flipkart-header/assets/73392705/deceb369-773b-434b-919d-aabf5e76d248)

- The variety section displays various product categories.

## CSS Explanation

### Global Styles
- The `*` selector is used to reset margin, padding, and box-sizing for all elements to ensure consistent styling.
- The `body` element sets the font family to 'Roboto, sans-serif' for the entire document.

### Container (`.container`)
- The `.container` class styles the container for the entire content.
  - `width: 100%;`: Sets the width to 100% to span the full viewport width.
  - `max-width: 1150px;`: Sets the maximum width of the container to 1150 pixels.
  - `margin: 0 auto;`: Centers the container horizontally by setting the left and right margins to auto.

### Header Section (`.header` and `nav`)
- The `.header` class styles the header section.
  - `background: #2874f0;`: Sets the background color of the header to `#2874f0`.
  - `padding: .6% 0;`: Adds padding to the header for spacing.

- The `nav` element styles the navigation bar.
  - `display: flex;`: Makes the navigation bar a flex container.
  - `align-items: center;`: Centers items vertically.
  - `margin-right: 1%;`: Adds margin to the right of the navigation bar.

  - Logo (`.logo`):
    - `display: flex;`: Makes the logo a flex container with a column layout.
    - `flex-direction: column;`: Sets the direction to column.
    - `width: 7%;`: Sets the width of the logo container.
    - `margin-right: 1%;`: Adds margin to the right of the logo container.

    - Logo Image (`.logo-image`):
      - `width: 75px;`: Sets the width of the logo image to `75px`.
      - `margin-bottom: -5%;`: Adds negative margin to the bottom of the logo image to align it properly.

    - Explore Plus (`.explore-plus`):
      - `font-size: 11px;`: Sets the font size of the explore plus text to `11px`.
      - `font-style: italic;`: Makes the text italic.
      - `color: white;`: Sets the text color to white (`#ffffff`).
      - `text-decoration: none;`: Removes underlining from the link.

      - Explore Plus Span (`.explore-plus span`):
        - `margin-right: 5%;`: Adds margin to the right of the span.
        - `color: #ffe500;`: Sets the color of the span text to yellow (`#ffe500`).

### Search Bar (`.search-bar`)
- The `.search-bar` class styles the search bar.
  - `width: 45%;`: Sets the width of the search bar to `45%`.
  - `display: flex;`: Makes it a flex container.
  - `margin-right: 5%;`: Adds margin to the right for spacing.

  - Search Input (`.search-bar input`):
    - `width: 92%;`: Sets the width of the input field to `92%`.
    - `padding: 1.8% 2%;`: Adds padding to the input field (`1.8% 2%`).
    - `border: none;`: Removes the border from the input field.
    - `outline: none;`: Removes the outline when the input is focused.

  - Search Button (`.search-btn`):
    - `width: 8%;`: Sets the width of the search button to `8%`.
    - `border: none;`: Sets the border color to white (`#ffffff`).
    - `background: white;`: Sets the background color to white.
    - `display: flex;`: Makes the button a flex container.
    - `justify-content: center;`: Centers content horizontally.
    - `align-items: center;`: Centers content vertically.
    - `cursor: pointer;`: Changes the cursor to a pointer.

### Buttons (`.login-btn`, `.become-seller-btn`, `.more-btn`, `.cart-btn`)
- These classes style various buttons.
  - `font-weight: 500;`: Sets the font weight to `500`.
  - `background-color: #fff;`: Defines the background color as white.
  - `cursor: pointer;`: Changes the cursor to a pointer on hover.
  - `border-radius: 2px;`: Adds rounded corners with a radius of `2px`.
  - `height: 32px;`: Sets the height of the buttons to `32px`.
  - `padding: 5px 40px;`: Adds padding to the buttons (`5px` top and bottom, `40px` left and right).
  - `border: 1px solid #dbdbdb;`: Adds a `1px` solid border with a light gray color (`#dbdbdb`).

  - Button Links (`.link a`):
    - `font-size: 16px;`: Sets the font size to `16px`.
    - `letter-spacing: .1px;`: Adjusts the letter spacing to `.1px`.
    - `color: #fff;`: Sets the text color to white (`#ffffff`).
    - `line-height: 20px;`: Sets the line height to `20px`.
    - `text-decoration: none;`: Removes underlining from the links.
    - `text-transform: uppercase;`: Converts text to uppercase.

  - Login Button (`.login-btn`):
    - `background-color: #fff;`: Sets the background color to white (`#ffffff`).
    - `cursor: pointer;`: Changes the cursor to a pointer.

    - Login Button Link (`.login-btn a`):
      - `color: #2874f0;`: Sets the text color to Flipkart blue (`#2874f0`).

### Navigation Items (`.nav-item`)
- The `.nav-item` class styles navigation items.
  - `display: flex;`: Arranges items horizontally.
  - `margin: ...;`: Adds vertical spacing.
  - `align-items: ...;`: Vertically centers content.
  - `justify-content: ...;`: Spaces content evenly.
  - `cursor: ...;`: Indicates interactivity.
  - `transition: ...;`: Adds a smooth hover effect.

### More Button (`.more-btn svg`)
- The `svg` within the more button:
  - `transform: rotate(270deg);`: Rotates the SVG to `270deg` for an arrow effect.

### Variety Section (`.variety`)
- The `.variety` class styles the variety section.
  - `padding: 1% 0;`: Adds padding to the top and bottom of the section.

### Variety Items (`.variety-items`)
- The `.variety-items` class styles the container for variety items.
  - `display: flex;`: Uses flex to arrange items horizontally.
  - `justify-content: ...;`: Spaces items evenly.
  - `align-items: ...;`: Centers items vertically.
  - `list-style: ...;`: Removes the default list styles.

### Variety Item (`.item a`)
- The `.item a` class styles individual variety items.
  - `width: max-content;`: Sets the width of the item.
  - `display: flex;`: Arranges content in a column with space in-between.
  - `align-items: center;`: Centers content vertically.
  - `justify-content: ...;`: Provides space between content.
  - `text-decoration: none;`: Removes underlining from links.
  - `font-weight: 500;`: Sets the font weight to `500`.
  - `font-size: 14px;`: Adjusts the font size.
  - `transition: .2s;`: Adds a smooth transition effect on hover.

  - Variety Item Images (`.variety-image`):
    - `width: 64px;`: Sets the width of the variety item image.
    - `margin-bottom: 5%;`: Adds a small margin to the bottom for spacing.

- On hover, the `color` of the item's text changes to the Flipkart blue color (`#2874f0`).

