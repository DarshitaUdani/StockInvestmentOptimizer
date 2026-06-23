# 📈 Stock Investment Optimizer

A web-based application that helps investors maximize their expected returns using the **Fractional Knapsack Algorithm**. The application allows users to enter stock prices, expected returns, and a total investment budget, then calculates the optimal allocation of funds to achieve the highest possible return.

---

## 🚀 Features

- Dynamic stock input generation
- User-friendly and responsive interface
- Fractional investment support
- Calculates maximum expected return
- Displays detailed allocation breakdown
- Shows budget spent and remaining budget
- Implemented using the Fractional Knapsack Greedy Algorithm

---

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript (Vanilla JS)

---

## 📖 Algorithm Used

### Fractional Knapsack Algorithm

The Fractional Knapsack Algorithm is a greedy approach used to maximize profit when fractions of items can be selected.

#### Steps:

1. Calculate the return-to-price ratio for each stock.

2. Sort all stocks in descending order of their ratio.

3. Invest in stocks with the highest ratio first.

4. If the remaining budget is insufficient to buy an entire stock, invest a fraction of that stock.

5. Continue until the budget is exhausted.

### Time Complexity

- Sorting Stocks: **O(n log n)**
- Allocation Process: **O(n)**

Overall Complexity: **O(n log n)**

---

## 📂 Project Structure

```text
Stock-Investment-Optimizer/
│
├── index.html
├── README.md
└── assets/
```

---

## ▶️ How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/stock-investment-optimizer.git
```

2. Open the project folder.

3. Open `index.html` in a web browser.

4. Enter stock details and budget.

5. Click **Calculate Maximum Return**.

---

## 🎯 Applications

- Investment planning
- Portfolio optimization
- Financial decision support
- Learning Greedy Algorithms
- Educational demonstrations of Fractional Knapsack

---

## 🔮 Future Enhancements

- Real-time stock market integration
- Risk analysis and diversification suggestions
- Historical performance visualization
- Data export (PDF/Excel)
- Portfolio comparison tools

---

## 👩‍💻 Author

Developed as a project demonstrating the practical application of the Fractional Knapsack Algorithm in stock investment optimization.

---

## 📜 License

This project is open-source and available under the MIT License.
