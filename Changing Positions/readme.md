# CSS Positioning Project

### Objective:
This project focuses on implementing various CSS positioning techniques (relative, absolute, fixed, and sticky) on HTML elements within a container. 

---

## 🎯 **Task Requirements**

### 1. **Project Structure**:
   - **Container**:
     - A `div` element with the class `.container` containing four child `div` elements, each with unique IDs:
       - `relativeBox`
       - `absoluteBox`
       - `fixedBox`
       - `stickyBox`

---

## 📏 **CSS Positioning Specifications**

### 1. **Relative Positioning: `relativeBox`**
   - **Positioning**: `relative`
   - **CSS Rules**:
     - `top`: `20px` from its normal position
     - `width`: `200px`
     - `height`: `100px`
     - `margin-top`: `50px`

### 2. **Absolute Positioning: `absoluteBox`**
   - **Positioning**: `absolute`
   - **CSS Rules**:
     - Positioned `200px` from the top of its nearest positioned ancestor (if none, the nearest positioned ancestor is the viewport).
     - Positioned `50px` from the left.
     - `width`: `200px`
     - `height`: `100px`

### 3. **Fixed Positioning: `fixedBox`**
   - **Positioning**: `fixed`
   - **CSS Rules**:
     - Positioned in the **bottom right corner** of the viewport.
     - `width`: `200px`
     - `height`: `100px`

### 4. **Sticky Positioning: `stickyBox`**
   - **Positioning**: `sticky`
   - **CSS Rules**:
     - Sticks to the **top of its container** when scrolling.
     - `width`: `200px`
     - `height`: `100px`
     - `margin-top`: `150px`
     
---

## 📘 **Usage Notes**
- **Relative Positioning** adjusts an element's position based on its original location in the document flow.
- **Absolute Positioning** removes the element from the document flow and positions it relative to the closest positioned ancestor.
- **Fixed Positioning** positions an element in a fixed location on the viewport, regardless of scrolling.
- **Sticky Positioning** allows the element to act as relatively positioned until it reaches a scroll threshold, after which it behaves as fixed.

---

https://github.com/user-attachments/assets/7762adc7-7406-4ace-a910-e78a8a25f92f



This project explores how different CSS positioning techniques influence the layout and appearance of elements within a container, giving you hands-on practice with CSS positioning properties.
