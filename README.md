# 💰 Income Tax Calculator

A simple **Income Tax Calculator web application** built using **HTML, CSS, and JavaScript**.  
It calculates tax based on predefined income slabs and displays the result instantly on form submission.

---

## 🚀 Features
- User-friendly income input form
- Automatic tax calculation based on income slabs
- Real-time result display
- Form reset after calculation
- Clean and simple logic implementation

---

## 🛠️ Tech Stack
- HTML5
- CSS3
- JavaScript (Vanilla JS)

---

## 📊 Tax Slab Structure

<table border="1" cellpadding="10" cellspacing="0">
  <thead>
    <tr>
      <th>Annual Income (₹)</th>
      <th>Tax Rate</th>
      <th>Tax Calculation</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Up to 12,00,000</td>
      <td>0%</td>
      <td>No Tax</td>
    </tr>
    <tr>
      <td>12,00,001 – 16,00,000</td>
      <td>15%</td>
      <td>(Income − 12,00,000) × 15%</td>
    </tr>
    <tr>
      <td>16,00,001 – 20,00,000</td>
      <td>20%</td>
      <td>(Income − 16,00,000) × 20% + ₹60,000</td>
    </tr>
    <tr>
      <td>20,00,001 – 24,00,000</td>
      <td>25%</td>
      <td>(Income − 20,00,000) × 25% + ₹1,40,000</td>
    </tr>
    <tr>
      <td>Above 24,00,000</td>
      <td>30%</td>
      <td>(Income − 24,00,000) × 30% + ₹2,40,000</td>
    </tr>
  </tbody>
</table>


---

## ⚙️ How It Works
1. User enters annual income
2. On form submission:
   - JavaScript checks applicable tax slab
   - Calculates tax using conditional logic
3. Tax amount is displayed dynamically
4. Form resets for next calculation

---

## 📂 Project Structure
income-tax-calculator/<br>
│      <br>
├── index.html  <br>
├── style.css   <br>
└── script.js    <br>


---

## 🌐 Live Demo
👉 https://your-username.github.io/income-tax-calculator/

*(Enable GitHub Pages to view live demo)*

---

## 📸 Screenshot
*(Add a screenshot here for better presentation)*

---

## 🎯 Future Improvements
- Add multiple tax regimes
- Show detailed tax breakdown
- Input validation & error handling
- Responsive UI enhancements

---

## 📄 License
This project is open-source and intended for learning and practice purposes.
