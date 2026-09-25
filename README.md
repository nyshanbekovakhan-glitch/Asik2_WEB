 Web Technologies-1

**Name:** Khanzada Nyshanbek Adilqyzy
**Group:** SE-2539

 Part 1. Flexbox

 Task 0. Navigation Bar

1. Create a header section with a logo on the left and a list of links on the right.

![Screenshot](Снимок%20экрана%202026-09-25%20в%2009.32.45.png)

2. Turn the header container into a flex container.

![Screenshot](Снимок%20экрана%202026-09-25%20в%2009.33.45.png)

3. Align the logo and the links horizontally.

![Screenshot](Снимок%20экрана%202026-09-25%20в%2009.48.16.png)

4. Apply spacing between the links using Flexbox properties.

![Screenshot](Снимок%20экрана%202026-09-25%20в%2009.52.04.png)

5. Make sure the logo and links are vertically centered.

![Screenshot](Снимок%20экрана%202026-09-25%20в%2009.53.30.png)

 Task 1. Card Row

1. Create a container with at least three cards (each card should include an image, title, text, and button).

![Screenshot](Снимок%20экрана%202026-09-25%20в%2010.05.31.png)

2. Make the container a flex container so the cards appear in a row.

![Screenshot](Снимок%20экрана%202026-09-25%20в%2010.07.21.png)

3. Ensure all cards have equal height.

![Screenshot](Снимок%20экрана%202026-09-25%20в%2010.11.22.png)

4. Add consistent gaps between the cards.

![Screenshot](Снимок%20экрана%202026-09-25%20в%2010.12.15.png)

5. Add a simple hover effect (e.g., shadow, lift, or scale).

![Screenshot](Снимок%20экрана%202026-09-25%20в%2010.34.54.png)

Part 2. Grid System

Task 2. Page Layout with Grid Areas

1. Set up a layout with a header, sidebar, main content, and footer.

![Screenshot](Снимок%20экрана%202026-09-25%20в%2010.44.46.png)

2. Turn the parent container into a grid container.

![Screenshot](Снимок%20экрана%202026-09-25%20в%2010.45.56.png)

3. Define grid rows and columns.

![Screenshot](Снимок%20экрана%202026-09-25%20в%2010.48.16.png)

4. Assign grid areas so that:

   * The header spans across the top,
   * The sidebar is placed on the left,
   * The main content is on the right,
   * The footer spans across the bottom.

![Screenshot](Снимок%20экрана%202026-09-25%20в%2010.54.15.png)

5. Confirm that each section fits correctly into its grid area.

Task 3. Image Gallery

1. Collect at least nine images and place them inside a gallery container.

![Screenshot](Снимок%20экрана%202026-09-25%20в%2011.12.13.png)

2. Set the gallery container as a grid container.

![Screenshot](Снимок%20экрана%202026-09-25%20в%2011.13.12.png)

3. Define multiple equal-width columns and rows.

![Screenshot](Снимок%20экрана%202026-09-25%20в%2011.16.09.png)

4. Add consistent spacing (gaps) between images.

![Screenshot](Снимок%20экрана%202026-09-25%20в%2011.27.17.png)

5. Add a hover effect — for example, display a caption overlay when the user hovers over an image.

![Screenshot](Снимок%20экрана%202026-09-25%20в%2011.54.37.png)

![Screenshot](Снимок%20экрана%202026-09-25%20в%2011.54.45.png)

 Part 3. Combining Flexbox & Grid
 Task 4. Portfolio Page

1. Create a page structure with: header, main section, sidebar, and footer.

![Screenshot](Снимок%20экрана%202026-09-25%20в%2013.56.50.png)

2. Use **Flexbox** in the header for the navigation bar.

![Screenshot](Снимок%20экрана%202026-09-25%20в%2014.01.32.png)

3. Use **CSS Grid** for the main section:

   * Projects area on the left,
   * Info or sidebar on the right.

![Screenshot](Снимок%20экрана%202026-09-25%20в%2014.05.57.png)

4. Inside each project card, use Flexbox to arrange content (title, description, button).

![Screenshot](Снимок%20экрана%202026-09-25%20в%2014.19.03.png)

5. Ensure the footer spans across the bottom of the page.

![Screenshot](Снимок%20экрана%202026-09-25%20в%2014.19.21.png)

Summary

Today I learned about CSS Flexbox and Grid. These are layout systems that help us arrange elements on a web page.
First, I learned Flexbox. Flexbox is a one-dimensional layout method for arranging items in rows or columns. To use Flexbox, I use `display: flex`. The parent element becomes a flex container, and its direct children become flex items. I also learned about the main axis and cross axis. The main axis is the primary direction where the items are placed, and the cross axis is perpendicular to it.
I learned important Flexbox properties such as `flex-direction`, `justify-content`, `align-items`, and `flex-wrap`. For example, `flex-direction` defines the direction of the items, `justify-content` aligns items on the main axis, and `align-items` aligns items on the cross axis.
Then I learned CSS Grid. Grid is a two-dimensional layout system that works with rows and columns. A parent with `display: grid` becomes a grid container, and its children become grid items. We learned about grid rows, columns, cells, tracks, areas, and lines.
I also learned special Grid units and functions. The most important one for me is `fr`, which represents a fraction of the available space. For example, `grid-template-columns: 1fr 1fr` creates two equal columns. We also learned `repeat()`, `auto`, `min-content`, `max-content`, `minmax()`, and `fit-content()`.
For Grid properties, I learned `grid-template-columns`, `grid-template-rows`, `gap`, `grid-column`, `grid-row`, and `grid-area`. `gap` is used to create consistent spacing between grid items.
I also learned the difference between Flexbox and Grid. Flexbox is one-dimensional, so it is useful for navigation bars, menus, buttons, and simple alignment. Grid is two-dimensional, so it is useful for full page layouts, galleries, dashboards, and more complex designs.
Finally, I learned that Flexbox and Grid can be combined. For example, we can use Grid for the main page layout and Flexbox inside a card to arrange its content. In our Portfolio Page, we used Flexbox in the header and inside project cards, while we used Grid for the main section with Projects on the left and Sidebar on the right.

Overall, I learned how to use Flexbox and Grid to create organized layouts with consistent spacing and alignment.


