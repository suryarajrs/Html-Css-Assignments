# Responsive Grid Layout with CSS Grid

### Objective:
Build a responsive grid layout containing 12 cards using CSS Grid, where the grid container resizes while maintaining three items per row, regardless of screen size.

---

## 🎯 **Task Requirements**

### 1. **Parent Container (`.cards`)**
   - **Class Name**: `.cards`
   - **CSS Properties**:
     - `display`: Set to `grid` for CSS Grid layout.
     - `grid-template-columns`: Use the `repeat()` function to ensure **3 items per row**, with each item occupying `1fr` of space.
       ```css
       grid-template-columns: repeat(3, 1fr);
       ```
     - `grid-gap`: Set to `1rem` to space items evenly.

### 2. **Child Elements (`.card`)**
   - **Class Name**: `.card`
   - **Content**: Each `.card` div contains capitalized text:
      - **Values**: ONE, TWO, THREE, ... up to TWELVE
   - **Count**: Total of 12 `.card` elements within the `.cards` container.

---

## 📘 **Usage Notes**
- **Responsive Design**:
  - The grid will automatically resize based on the parent container (`.cards`) dimensions while maintaining three `.card` elements per row.
- **CSS Grid Features**:
  - The `repeat()` function in `grid-template-columns` ensures a flexible and scalable design, as each `.card` will occupy equal space (`1fr`) in each row.

This project provides hands-on practice with CSS Grid layout, focusing on responsive design and uniform grid spacing.


https://github.com/user-attachments/assets/083bfb75-2943-4ae8-80e8-a46f89ca2dd1

