# BMI-calculator <br>
This is a **BMI (Body Mass Index) Calculator** web page built using **HTML, CSS, and JavaScript**.  

### **Code Breakdown:**

#### **1. HTML (Structure)**
- Defines a simple form inside a `div` with a class **box** to input user details:
  - Age input field.
  - Gender selection (radio buttons).
  - Height input (in meters).
  - Weight input (in kg).
  - A **button** to calculate BMI when clicked.
- The form is centered inside a `div` with class **container**.

#### **2. CSS (Styling)**
- The page has a **pink** background with a flexbox layout to center the BMI form.
- The input fields and button are styled with:
  - Rounded corners.
  - Proper padding for better user experience.
  - A hover effect on the button (changes to grey when hovered).

#### **3. JavaScript (Functionality)**
- The `bmi()` function calculates the **BMI** based on the input height and weight.
- The formula used:  
  \[
  BMI = \frac{\text{Weight (kg)}}{\text{Height (m)}^2}
  \]
- The BMI result is categorized into:
  - **Severe Thinness**: BMI < 16
  - **Normal**: BMI between 18.5 - 25
  - **Overweight**: BMI > 26
  - **Obese**: Other cases

- The result is displayed using an **alert message**.

### **Issues & Improvements:**
1. **Incorrect BMI range conditions:**
   - The `else if (valueofbmi > 26)` condition ignores BMI between **25-26**.
   - A correct range should be `else if (valueofbmi > 25 && valueofbmi <= 30)`.
  
2. **Missing input validation:**
   - No checks if fields are empty or negative values are entered.

3. **No BMI output display on the page:**
   - Instead of an alert, the result could be displayed dynamically within a paragraph `<p>`.

Would you like me to improve this code for you? 🚀
