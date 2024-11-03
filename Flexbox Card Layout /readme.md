# 🃏 Flexbox Card Layout Project

### Objective:
Create a responsive card layout using Flexbox, featuring images, titles, descriptions, and buttons within each card.

---

## 📋 **Project Requirements**

### 1. **HTML Structure**
   - **Card Container**: Create a `div` with the class `card-container`.
   - **Cards**: Inside the container, create four `div` elements with the class `card`. Each card will contain:
     - **Image**: An `img` element with the `src` set to `https://picsum.photos/300/200` (for placeholder images) and `alt` attribute set to "Card Image".
     - **Title**: An `h2` element with the text "Card Title N" (where N is 1 through 4).
     - **Description**: A `p` element containing the following text:
       ```
       Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc ut libero eget mi tristique egestas.
       ```
     - **Button**: A `button` element with the text "Read More".

### 2. **CSS Styling**
   - **Card Container** (`.card-container`):
     - Set `display: flex` to enable Flexbox layout.
     - Use `flex-wrap: wrap` to allow items to wrap onto multiple lines.
     - Center the items horizontally with `justify-content: center`.
     - Set `font-family` to:
       ```
       Noto -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif, Arial;
       ```

   - **Card Styling** (`.card`):
     - Width: `300px`
     - Margin: `10px`
     - Padding: `20px`
     - Background color: `#f2f2f2`
     - Border-radius: `5px`

   - **Image Styling** (`.card img`):
     - Width: `100%`
     - Border-radius: `5px`
     - Margin-bottom: `10px`

   - **Heading Styling** (`.card h2`):
     - Font size: `18px`
     - Margin-bottom: `10px`

   - **Paragraph Styling** (`.card p`):
     - Margin-bottom: `10px`

   - **Button Styling** (`.card button`):
     - Background color: `#4CAF50`
     - Text color: `white`
     - Padding: `10px` vertical, `20px` horizontal
     - Border: `none`
     - Border-radius: `3px`
     - Cursor: `pointer` (for hover effect)

---

## 🛠 **Setup Instructions**

1. **Clone Repository**:
    ```bash
    git clone https://github.com/your-username/flexbox-card-layout.git
    ```

2. **Open `index.html`** in your browser to see the card layout in action.

### 📽 Demo Video
Watch the [demo video]() to see how the layout works.


https://github.com/user-attachments/assets/de21de6e-94c2-4563-bb1f-20b1ed59c01e


---
