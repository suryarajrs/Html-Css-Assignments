# Feedback Form

### Objective:
This form allows users to submit their name, portfolio URL, favorite color, and a rating of how much they like their color. The form uses the `POST` method and incorporates various validation rules to ensure proper data submission.

---

## 📋 **Form Details**:

### 1. **Name Input:**
- **ID**: `name`
- **Validation**:
  - Must be a **required** field.
  - Minimum of **3 characters** and maximum of **50 characters**.
- **Label**: 
  - The label for this field is:  
    `Name`
    
---

### 2. **Portfolio URL:**
- **ID**: `portfolio`
- **Validation**:
  - This field is **required** and must be a valid URL.
- **Label**: 
  - The label for this field is:  
    `Portfolio URL`

---

### 3. **Favorite Color:**
- **ID**: `favColor`
- **Input Type**: Color picker, allowing users to select their preferred color.
- **Label**:
  - The label for this field is:  
    `Favorite Color`

---

### 4. **Likeness Slider:**
- **ID**: `likeness`
- **Input Type**: Range slider.
- **Range**: From **1** to **100**, allowing users to rate how much they like their chosen color.
- **Label**:
  - The label for this field is:  
    `How much do you like your color?`

---

### 5. **Submit Button:**
- **Type**: Submit button for form submission.
- **Button Text**:  
    `Submit`

---

## 🎯 **Form Submission Requirements**:
- The form uses the `POST` method for data submission.
- Both the **Name** and **Portfolio URL** fields are **required** for successful submission.
- Validation rules are applied to ensure proper input.

This form enables users to interactively provide feedback while ensuring all required details are collected correctly.

## Output should looks like this

<img width="574" alt="feedbackform" src="https://github.com/user-attachments/assets/40d1c74b-e99c-4de3-bc11-6bb517dd8456">
