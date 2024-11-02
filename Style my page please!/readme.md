# 🖌️ HTML Structure Styling Guide

### Objective
To apply styles to a given HTML structure, focusing on layout, positioning, and hover effects using CSS. This guide provides the styling requirements for the `#main-container`, `#header`, `#footer`, and other nested elements.

---

## 🎨 **Styling Instructions**

### 1. **Main Container Styling** (`#main-container`)
   - **Width**: Set to `100%`.

### 2. **Header and Footer Styling** (`#header` & `#footer`)
   - **Display**: Set to `block`.
   - **Width**: `100%`.
   - **Padding**: `20px` for both the top and bottom.
   - **Text Alignment**: Center.
   - **Background Colors**:
      - `#header`: Light Gray.
      - `#footer`: Dim Gray.

### 3. **Navbar Items Styling** (`.nav-item` within `#navbar`)
   - **Display**: Inline Block.
   - **Padding**: `10px` top and bottom; `20px` left and right.
   - **Hover Effect**:
      - Background color changes to `rgba(0, 0, 0, 0.1)` on hover.
      - **Transition**: `background-color` changes over `0.3s`.

### 4. **Content Section Styling** (`#content`)
   - **Display**: Flexbox.
   - **Flex Wrap**: Items should wrap using `wrap`.
   - **Gap Between Flex Items**: `16px`.

### 5. **Individual Article Item Styling** (`.article-item` within `#content`)
   - **Flex Grow**: Each item grows equally, using `flex: 1`.
   - **Padding**: `20px`.
   - **Special Item (`#post1`)**:
      - Should occupy **twice as much space** as other `.article-item` elements with `flex: 2`.

---

### final output should look like this
![73785f0160984cb483ff823891655aa3](https://github.com/user-attachments/assets/222e61af-93fb-4d05-b06a-6366c7e83607)

