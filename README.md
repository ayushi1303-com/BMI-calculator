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

