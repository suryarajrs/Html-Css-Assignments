# CSS Shapes: Box and Circle with Container Layout

This guide explains how to create visually distinct shapes (`.box` and `.circle`) within a flex container (`.container`). Below is a structured overview of their characteristics and layout design.

---

## CSS Classes and Their Properties

### 1. `.box` Class: Square Shape

- **Dimensions**: 
  - Height: `100px`
  - Width: `100px`
- **Border**: 
  - Thickness: `1px`
  - Style: `solid`
  - Color: `black`
- **Padding**: `10px` (inside spacing between content and border).
- **Margin**: `10px` (outside spacing around the element).
- **Background Color**: `pink`

### 2. `.circle` Class: Circular Shape

- **Dimensions**:
  - Height: `100px`
  - Width: `100px` (equal dimensions ensure a perfect circle when combined with border-radius).
- **Border**:
  - Thickness: `1px`
  - Style: `solid`
  - Color: `black`
- **Padding**: `10px` (inside spacing between content and border).
- **Margin**: `10px` (outside spacing around the element).
- **Background Color**: `red`
- **Border-Radius**: `50%` (creates the circular appearance).

### 3. `.container` Class: Layout Container

- **Display**: `flex` (for flexible and responsive layout).
- **Alignment**:
  - `align-items: center` (vertical alignment of child elements in the center).
- **Purpose**: Acts as a parent div to house and arrange `.box` and `.circle` elements.

---

## Visual Representation

- **Box and Circle**:
  - `.box`: A pink square with spacing inside and around it.
  - `.circle`: A red circle styled similarly but with a rounded shape.
- **Container Layout**:
  - Flexbox alignment ensures the elements are neatly centered within the container.

---

## Enhancements

- Add hover effects to make shapes interactive:
  - Example: Change background color on hover.
- Use media queries to make shapes responsive for various screen sizes.
- Extend `.container` properties for dynamic alignment (e.g., `justify-content`).

---

This layout is perfect for showcasing basic CSS properties and flexbox capabilities in a clean and visually appealing manner.

## Output
![image](https://github.com/user-attachments/assets/1cb0d021-740c-44c0-9116-5ead89316a8a)
