# finance-notes
finance notes lol

### **Present Value and Discounting**
Present value (PV) is the concept that money today is worth more than the same amount in the future due to the time value of money (TVM). This is because money today can be invested to earn a return. 

**Formula for Present Value:**
\[
PV = \frac{FV}{(1 + r)^t}
\]
Where:
- \( PV \) = Present Value
- \( FV \) = Future Value
- \( r \) = Discount rate (interest rate)
- \( t \) = Number of periods

**Discounting** is the process of finding the present value of a future cash flow by reversing compounding. It helps in valuing investments, pricing bonds, and making business decisions.

### **Perpetuities vs. Annuities**
Both perpetuities and annuities involve a series of cash flows over time, but they differ in duration.

#### **Perpetuity**
A perpetuity is a stream of equal cash flows that continues indefinitely. The present value of a perpetuity is calculated as:

\[
PV = \frac{C}{r}
\]

Where:
- \( C \) = Constant cash flow per period
- \( r \) = Discount rate

📌 **Example**: A preferred stock that pays a fixed dividend of $5 per year forever, with a required return of 10%, has a present value of:
\[
PV = \frac{5}{0.10} = 50
\]

#### **Annuity**
An annuity is a series of equal cash flows received or paid over a finite period. 

**Present Value of an Annuity Formula:**
\[
PV = C \times \left( 1 - \frac{1}{(1 + r)^t} \right) \div r
\]

Where:
- \( C \) = Cash flow per period
- \( r \) = Discount rate per period
- \( t \) = Number of periods

📌 **Example**: If you receive $1,000 annually for 5 years at a 10% discount rate, the present value is:
\[
PV = 1000 \times \left( 1 - \frac{1}{(1.10)^5} \right) \div 0.10
\]

Annuities can be:
- **Ordinary annuities** (payments occur at the end of each period).
- **Annuities due** (payments occur at the beginning of each period). The formula for annuities due adjusts by multiplying by \( (1+r) \).

### **Net Present Value (NPV)**
**Net Present Value (NPV)** is a fundamental concept in finance used to evaluate investment opportunities. It measures the difference between the present value of cash inflows and the present value of cash outflows over time.

#### **NPV Formula:**
\[
NPV = \sum \frac{C_t}{(1 + r)^t} - C_0
\]
Where:
- \( C_t \) = Cash flow in period \( t \)
- \( r \) = Discount rate (cost of capital)
- \( t \) = Time period
- \( C_0 \) = Initial investment (cash outflow at \( t = 0 \))

📌 **Key Interpretation:**
- **NPV > 0** → The project is expected to create value and should be accepted.
- **NPV < 0** → The project is expected to destroy value and should be rejected.
- **NPV = 0** → The project breaks even but does not create additional value.

---

### **Why is NPV the Right Concept for Decision Making?**
1. **Incorporates the Time Value of Money (TVM)**  
   - NPV discounts future cash flows to reflect their present worth, ensuring an accurate measure of value.

2. **Considers All Relevant Cash Flows**  
   - Unlike accounting profit, NPV evaluates real cash inflows and outflows over time.

3. **Uses a Risk-Adjusted Discount Rate**  
   - The discount rate reflects the cost of capital and the riskiness of future cash flows, ensuring an appropriate valuation.

4. **Directly Measures Value Creation**  
   - A positive NPV means the project increases shareholder value, making it a clear decision rule.

5. **Avoids Arbitrary Cutoffs**  
   - Unlike Payback Period, which ignores cash flows beyond a certain point, NPV considers the entire lifespan of the project.

6. **Works Well for Mutually Exclusive Projects**  
   - When choosing between alternatives, the project with the highest positive NPV is the best choice.

📌 **Example**:  
If a firm is deciding whether to invest in a new machine that costs $50,000 and is expected to generate $15,000 per year for 5 years at a 10% discount rate, NPV helps determine if the investment is worthwhile.


### **The Goal of the Firm and the NPV Rule**

#### **1. The Goal of the Firm: Maximizing Shareholder Wealth**
The primary objective of a firm, particularly in finance, is to **maximize shareholder wealth**. This goal aligns with creating value for shareholders, which is typically measured by the market value of the firm’s stock.

📌 **Why Maximizing Shareholder Wealth?**  
- It reflects the long-term financial success of the company.
- Share prices incorporate expectations about future cash flows and risks.
- It ensures efficient capital allocation, benefiting investors and the economy.

While other goals exist—such as profit maximization, market share growth, or corporate social responsibility—the financial goal of maximizing **firm value** remains the most widely accepted because it accounts for both **risk and the time value of money**.

---

### **2. The NPV Rule and Its Role in Decision-Making**
The **Net Present Value (NPV) rule** is the most reliable decision-making criterion for firms when evaluating investment opportunities.

#### **The NPV Rule:**
- **Accept a project if NPV > 0** (It adds value to the firm and increases shareholder wealth).
- **Reject a project if NPV < 0** (It destroys value and should not be pursued).
- **Indifferent if NPV = 0** (The project neither adds nor subtracts value).

Since NPV represents the value added to the firm by undertaking a project, **maximizing NPV aligns perfectly with maximizing shareholder wealth**.

---

### **3. Why is NPV the Best Rule?**
1. **Accounts for the Time Value of Money (TVM)**  
   - Future cash flows are discounted to reflect their present worth.

2. **Considers All Cash Flows**  
   - Unlike the payback period, which ignores cash flows after a certain point, NPV includes the entire project life.

3. **Uses a Risk-Adjusted Discount Rate**  
   - Ensures that future cash flows are evaluated against an appropriate cost of capital.

4. **Directly Measures Value Creation**  
   - Unlike IRR (Internal Rate of Return), which can sometimes give misleading results, NPV always provides a clear decision rule.

5. **Handles Mutually Exclusive Projects Well**  
   - If choosing between projects, the one with the highest positive NPV should be selected.

---

### **4. Example of NPV in Action**
Suppose a firm is considering a project with the following details:
- **Initial Investment**: $100,000
- **Expected Annual Cash Flows**: $30,000 for 5 years
- **Required Return (Discount Rate)**: 10%

The **NPV** calculation:

\[
NPV = \sum \frac{30,000}{(1.10)^t} - 100,000
\]

If the NPV is **positive**, the firm should **accept** the project, as it adds value.

---

### **Conclusion**
The **goal of the firm is to maximize shareholder wealth**, and the **NPV rule is the best financial decision-making tool** because it:
✔ Incorporates the time value of money  
✔ Considers all relevant cash flows  
✔ Uses a risk-adjusted discount rate  
✔ Directly measures value creation  


### **The Goal of the Managers of the Firm**

The primary goal of **managers** within a firm should be to **maximize shareholder wealth**, aligning their decisions with the interests of the firm's owners (shareholders). This means making financial and strategic choices that increase the firm's stock price and overall market value.

---

### **1. Why Should Managers Focus on Maximizing Shareholder Wealth?**
1. **Direct Link to Firm Value**  
   - Shareholders are the ultimate owners of the firm. Maximizing stock price ensures that their investment grows.
   
2. **Efficient Capital Allocation**  
   - When managers prioritize value creation, they allocate resources to the most profitable projects, enhancing firm performance.

3. **Long-Term Sustainability**  
   - Focusing on sustainable, profitable growth rather than short-term gains ensures the firm remains competitive.

4. **Alignment with Financial Markets**  
   - Investors evaluate firms based on expected future cash flows. Maximizing shareholder wealth signals that the firm is well-managed.

---

### **2. Challenges to This Goal: Agency Problems**
Even though maximizing shareholder wealth should be the main objective, **agency problems** arise when managers act in their own interest rather than in the shareholders’ best interest.

📌 **Agency Problem:** A conflict between managers (agents) and shareholders (principals), where managers may pursue personal benefits (e.g., higher salaries, job security) instead of maximizing firm value.

🔹 **Examples of Agency Problems:**
- **Empire Building**: Managers pursue unnecessary expansions to increase their power.
- **Perquisite Consumption**: Using company resources for personal benefits (luxury offices, private jets).
- **Short-Termism**: Making decisions that boost short-term earnings at the expense of long-term value.

---

### **3. How to Align Managers’ Interests with Shareholders?**
To reduce agency problems, companies use various corporate governance mechanisms:

1. **Performance-Based Compensation**  
   - Stock options, bonuses, and equity-based incentives ensure managers’ rewards are tied to shareholder value.

2. **Board of Directors Oversight**  
   - An independent board monitors managerial actions and ensures accountability.

3. **Market for Corporate Control**  
   - If managers underperform, hostile takeovers or activist investors can pressure them to improve.

4. **Shareholder Activism**  
   - Institutional investors and activist shareholders can influence management decisions.

5. **Legal and Regulatory Framework**  
   - Securities laws (like Sarbanes-Oxley) enforce transparency and reduce unethical behavior.

---

### **4. Beyond Shareholder Wealth: Should Managers Consider Other Stakeholders?**
While shareholder wealth maximization is the primary financial objective, many argue that managers should also consider **stakeholder value**, including:
- Employees (fair wages, job security)
- Customers (quality products, fair pricing)
- Society (corporate social responsibility, environmental impact)

This approach, known as **stakeholder capitalism**, balances financial success with ethical and social responsibilities. However, from a finance perspective, **maximizing shareholder wealth remains the core objective, as long as it is done ethically and sustainably**.

---

### **Conclusion**
✔ The primary goal of managers should be **maximizing shareholder wealth** through value-creating decisions.  
✔ **Agency problems** can lead to conflicts, but incentives, oversight, and regulations help align interests.  
✔ **Balancing stakeholder interests** can enhance long-term shareholder value by ensuring sustainable and ethical growth.


### **Why Does Choosing Positive NPV Projects Maximize Shareholder Wealth?**

Choosing **positive Net Present Value (NPV) projects** is the best way for a firm to maximize shareholder wealth because NPV directly measures the value created by an investment. Here’s why:

---

### **1. NPV Measures the Increase in Firm Value**
- **NPV represents the dollar amount by which a project increases the firm's value.**  
- When a company undertakes a project with **NPV > 0**, the present value of future cash inflows **exceeds** the initial cost.  
- This means shareholders gain additional wealth, reflected in a higher stock price.

📌 **Example:**  
If a company undertakes a project with an **NPV of $1 million**, it directly increases the firm’s total market value by **$1 million**.

---

### **2. NPV Accounts for the Time Value of Money (TVM)**
- Future cash flows are discounted to their present value, ensuring a proper comparison with the initial investment.
- This prevents overestimating the project's benefits, unlike accounting-based measures like ROI or net income.

📌 **Why It Matters?**  
A project that generates $1 million in 10 years **is not worth $1 million today** due to inflation, risk, and the opportunity cost of capital.

---

### **3. NPV Considers All Relevant Cash Flows**
- NPV includes **all future expected cash flows**, unlike metrics like the **Payback Period**, which ignores cash flows beyond a cutoff.
- This comprehensive approach ensures better decision-making.

📌 **Example:**  
Two projects:
- Project A: Returns $50,000 per year for **3 years**.
- Project B: Returns $40,000 per year for **5 years**.

Even if Project A has a **faster payback**, Project B may have a **higher NPV** because it generates cash flows for longer.

---

### **4. NPV Uses a Risk-Adjusted Discount Rate**
- The **discount rate (\(r\))** reflects the project’s risk and the company’s **cost of capital (WACC)**.
- This ensures that only projects that generate returns above the firm’s required return are accepted.

📌 **Why It Matters?**  
- A project with a **20% return is great if the cost of capital is 10%**.  
- But if the cost of capital is **25%**, the project destroys value.  
- NPV ensures that only projects that **earn more than the required return** are chosen.

---

### **5. NPV Avoids Pitfalls of Other Decision Rules**
| Decision Rule | Potential Issue | Why NPV is Better |
|--------------|---------------|-----------------|
| **IRR (Internal Rate of Return)** | Can give **multiple or misleading rates** | NPV gives a clear dollar value |
| **Payback Period** | Ignores cash flows after cutoff | NPV includes all cash flows |
| **Profitability Index (PI)** | Good for ranking, but not for scale | NPV shows total dollar gain |

---

### **6. Maximizing NPV = Maximizing Shareholder Wealth**
Since **stock prices reflect the present value of expected future cash flows**, increasing firm value via positive NPV projects leads to:
- **Higher earnings per share (EPS)**
- **Higher dividends**
- **Higher stock prices**
- **Greater investor confidence**

📌 **Example:**  
If Tesla undertakes a project that adds $10 billion in NPV, its stock price is likely to increase because the company’s future expected cash flows have improved.

---

### **Conclusion: NPV = The Best Decision Rule**
✔ **NPV directly measures the value added to the firm.**  
✔ **NPV accounts for risk, time value of money, and all cash flows.**  
✔ **Accepting positive NPV projects increases stock prices and shareholder wealth.**  

💡 **Bottom Line**: Choosing positive NPV projects is the best way to achieve the firm’s goal of **maximizing shareholder wealth**. 


### **1. Unlevered Net Income vs. Net Income**
#### **Unlevered Net Income (Operating Income After Taxes)**
Unlevered net income represents the **profit a firm generates from operations**, **excluding** the impact of debt (i.e., before interest payments). It reflects how profitable a company is based purely on its operations.

📌 **Formula:**
\[
\text{Unlevered Net Income} = EBIT \times (1 - \text{Tax Rate})
\]
Where:
- **EBIT (Earnings Before Interest and Taxes)** represents the company’s operating profit.
- **(1 - Tax Rate)** adjusts for corporate taxes.

💡 **Why It Matters?**
- Provides a **debt-neutral** view of profitability.
- Helps evaluate business performance **independent of capital structure** (debt vs. equity).

---

#### **Net Income**
Net income is the **bottom-line profit** after deducting all expenses, including:
- **Operating expenses**
- **Taxes**
- **Interest on debt**

📌 **Formula:**
\[
\text{Net Income} = \text{EBIT} - \text{Interest} - \text{Taxes}
\]

💡 **Why It Matters?**
- Represents the **actual earnings** available to shareholders.
- Affected by financing decisions (**debt levels, interest expenses**).

📌 **Key Difference:**  
- **Unlevered Net Income** = Ignores financing decisions (debt) → **Useful for project evaluation (NPV).**  
- **Net Income** = Includes financing costs → **Useful for equity investors.**  

---

### **2. Definition of Free Cash Flow (FCF)**
Free Cash Flow (FCF) measures the **actual cash available** to investors after accounting for all expenses necessary to sustain the business. It represents the cash a firm can use for:
- **Reinvesting in the business**
- **Paying dividends**
- **Reducing debt**
- **Returning capital to shareholders**

📌 **Formula:**
\[
FCF = \text{Unlevered Net Income} + \text{Depreciation} - \text{Capital Expenditures} - \text{Change in Net Working Capital}
\]

Where:
- **Depreciation** is a non-cash expense (added back).
- **Capital Expenditures (CapEx)** represents investments in assets.
- **Change in Net Working Capital (NWC)** accounts for short-term liquidity needs.

💡 **Why It Matters?**
- **FCF represents real cash availability** (not just accounting profits).
- A company with high net income but **low or negative FCF** may struggle with cash flow issues.

---

### **3. Why is FCF the Right Number to Use in NPV Calculations?**
When calculating **Net Present Value (NPV)**, we use **Free Cash Flow (FCF) instead of Net Income** because:

1. **FCF Reflects True Economic Value**
   - Unlike net income, FCF **excludes non-cash expenses** (like depreciation) and includes real cash outflows (CapEx, working capital changes).
   - Net income can be **manipulated by accounting adjustments**, while FCF reflects **actual cash movement**.

2. **FCF is Available to All Investors**
   - **Net Income** only represents earnings available to **equity holders**.
   - **FCF represents cash flow available to both debt and equity investors**, making it the right number for project evaluation.

3. **NPV is Based on Cash Flows, Not Accounting Profits**
   - NPV measures how much actual **cash** an investment generates.
   - Using net income (which includes accounting assumptions like depreciation) would distort project valuation.

4. **FCF Accounts for Reinvestment Needs**
   - Businesses must reinvest in assets (CapEx) to sustain growth.
   - FCF subtracts CapEx and working capital changes, making it a **more accurate measure** of available cash.

---

### **Conclusion**
✔ **Unlevered Net Income** = Operating profit after taxes, before financing costs.  
✔ **Net Income** = Bottom-line earnings after interest and taxes.  
✔ **Free Cash Flow (FCF)** = Cash available to investors after all operating and capital expenses.  
✔ **NPV should use FCF** because:
   - It reflects real **cash availability**.
   - It **includes reinvestment needs**.
   - It is **available to all investors**, not just equity holders.


### **Dividend Discount Model (DDM) for Stock Valuation**
The **Dividend Discount Model (DDM)** is a fundamental stock valuation method that calculates the intrinsic value of a stock based on the present value of its future expected dividends.

The core assumption behind DDM is that a stock is worth the sum of all its future dividend payments, discounted back to present value.

---

### **1. General Formulation of the Dividend Discount Model**
The most general form of the DDM values a stock as the sum of all expected future dividends, discounted at the required rate of return:

\[
P_0 = \sum_{t=1}^{\infty} \frac{D_t}{(1 + r)^t}
\]

Where:
- \( P_0 \) = **Intrinsic value of the stock today**
- \( D_t \) = **Dividend expected in year \( t \)**
- \( r \) = **Required rate of return (cost of equity)**
- \( t \) = **Time period**

🔹 This general formula works for any pattern of dividends but can be complex if dividends **do not follow a predictable growth pattern**.

---

### **2. The Constant Dividend Growth Model (Gordon Growth Model)**
A simplified version of the general DDM assumes that dividends grow at a constant rate indefinitely. This is known as the **Gordon Growth Model (GGM)** and is commonly used for mature companies with stable dividend policies.

📌 **Formula:**
\[
P_0 = \frac{D_1}{r - g}
\]

Where:
- \( P_0 \) = **Stock price today**
- \( D_1 \) = **Dividend expected next year** (\(D_0 (1+g) \))
- \( r \) = **Required rate of return (cost of equity)**
- \( g \) = **Constant dividend growth rate** (must be less than \( r \))

🔹 **Key Assumption:** Dividends grow at a constant rate \( g \) **forever**.

---

### **3. Example of the Constant Growth Model**
Suppose:
- The company **paid a dividend of $2.00** last year (\( D_0 = 2.00 \)).
- The dividend is expected to grow at **5% per year** (\( g = 5\% \)).
- The required return on equity is **10%** (\( r = 10\% \)).

Step 1: Find \( D_1 \) (Next Year’s Dividend)
\[
D_1 = D_0 (1+g) = 2.00 \times (1.05) = 2.10
\]

Step 2: Apply the Gordon Growth Formula
\[
P_0 = \frac{2.10}{0.10 - 0.05} = \frac{2.10}{0.05} = 42.00
\]

📌 **Interpretation:**  
The stock is worth **$42.00 per share** based on expected future dividends.

---

### **4. When to Use the Constant Growth Model**
✅ **Best for**:
- **Stable, mature companies** with consistent dividend growth (e.g., utilities, consumer staples).
- Stocks with **long-term, predictable growth rates**.

❌ **Not suitable when**:
- The firm **does not pay dividends** (like many tech startups).
- Dividends **do not grow at a constant rate** (e.g., high-growth firms with fluctuating payouts).
- **The growth rate \( g \) is greater than or equal to \( r \)** (this would make the formula invalid).

---

### **Conclusion**
✔ **DDM values a stock based on its future expected dividends, discounted to present value.**  
✔ **The general model works for any dividend pattern but can be complex.**  
✔ **The Constant Growth Model (Gordon Growth Model) is a simplified version, assuming dividends grow at a steady rate forever.**  
✔ **It is useful for valuing stable, dividend-paying companies.**  


### **Investment and Growth in Firm Valuation**
Investment and growth are key drivers of firm value. The firm’s ability to reinvest earnings at a **high return on investment (ROI)** and generate sustainable growth is crucial for long-term valuation.

---

## **1. Price/Earnings (P/E) Ratio and the Present Value of Growth Opportunities (PVGO)**
The **Price/Earnings (P/E) ratio** is a widely used metric to value stocks. It represents how much investors are willing to pay for $1 of earnings.

\[
P/E = \frac{P_0}{E_1}
\]

Where:
- \( P_0 \) = Stock price today
- \( E_1 \) = Expected earnings per share (EPS) for next year

### **Decomposing the P/E Ratio: PVGO**
A firm's stock price consists of two components:
1. **The value of assets already in place (no-growth firm)**
2. **The present value of future growth opportunities (PVGO)**

\[
P_0 = \frac{E_1}{r} + PVGO
\]

Where:
- \( \frac{E_1}{r} \) is the value of the firm as if it had no growth.
- \( PVGO \) captures the value of future growth.

### **Interpretation of the P/E Ratio**
- **High P/E Ratio** → Indicates high expected growth (high PVGO).
- **Low P/E Ratio** → Suggests low growth potential or undervaluation.
- Growth firms typically have **higher P/E ratios**, while mature, low-growth firms have **lower P/E ratios**.

📌 **Example:**
- A utility company with stable earnings might have a **P/E of 10** (low PVGO).
- A tech startup with rapid growth expectations could have a **P/E of 50+** (high PVGO).

---

## **2. Reinvestment Ratio, Payout Ratio, and Return on Investment**
### **Reinvestment Ratio (Retention Ratio)**
The **Reinvestment Ratio** is the proportion of earnings that a firm reinvests in growth rather than paying out as dividends.

\[
\text{Reinvestment Ratio} = 1 - \text{Payout Ratio} = \frac{\text{Reinvestment in Growth}}{\text{Net Income}}
\]

📌 **Example:**
- If a firm earns $100M and reinvests $60M, the reinvestment ratio is:
  \[
  \frac{60}{100} = 60\%
  \]

---

### **Payout Ratio**
The **Payout Ratio** is the proportion of earnings paid out as dividends.

\[
\text{Payout Ratio} = \frac{\text{Dividends}}{\text{Net Income}}
\]

📌 **Example:**
- If a firm earns $100M and pays $40M in dividends:
  \[
  \frac{40}{100} = 40\%
  \]

📌 **Key Relationship:**
\[
\text{Reinvestment Ratio} + \text{Payout Ratio} = 1
\]
- **High growth firms** → High reinvestment ratio, low payout ratio.
- **Mature firms** → Low reinvestment ratio, high payout ratio.

---

### **Return on Investment (ROI) and Growth**
The growth rate (\( g \)) of a firm is determined by:

\[
g = \text{Reinvestment Ratio} \times \text{Return on Investment (ROI)}
\]

Where:
- **ROI** can be **Return on Equity (ROE)** or **Return on Invested Capital (ROIC)**.

📌 **Example:**
- A firm with:
  - **50% reinvestment ratio**
  - **20% ROI**
  - Growth rate = \( 0.5 \times 0.20 = 10\% \)

- If ROI is **low**, reinvesting earnings may not be beneficial.
- If ROI is **high**, reinvestment drives strong growth.

---

## **3. Constant Reinvestment with Constant ROI Example**
If a firm continuously reinvests earnings at a **constant return on investment**, its growth rate remains stable.

📌 **Example:**
- **Initial earnings**: $10M
- **Reinvestment ratio**: 40%
- **ROI**: 15%
- **Growth rate**: \( g = 0.40 \times 0.15 = 6\% \)
- **Year 1 earnings**: \( 10M \times 1.06 = 10.6M \)
- **Year 2 earnings**: \( 10.6M \times 1.06 = 11.24M \)
- **Stock valuation (Gordon Growth Model)**:
  \[
  P_0 = \frac{D_1}{r - g}
  \]

This model assumes **infinite reinvestment capacity** and a **stable ROI**.

---

## **4. Limits on Total Investment or Timing of Investment**
In reality, firms **face constraints** on reinvestment, such as:
1. **Size limits** → Only so many profitable projects exist.
2. **Market saturation** → Diminishing growth opportunities.
3. **Capital constraints** → Limited ability to raise funds.
4. **Regulatory limits** → External restrictions on expansion.

### **Example with Investment Limits**
A company in a **niche industry** may have:
- A **20% ROI** but **limited growth opportunities**.
- If reinvestment opportunities max out at **$50M per year**, growth is capped.

### **Example with Timing Constraints**
A **biotech company** investing in R&D may:
- Have **low short-term ROI** (early research).
- Experience **high ROI** later (patents, commercialization).
- Growth is **delayed**, requiring patience in valuation.

---

### **Conclusion**
✔ **P/E ratio reflects market expectations about future growth (PVGO).**  
✔ **Reinvestment Ratio + Payout Ratio = 1**, balancing growth vs. shareholder returns.  
✔ **Growth is driven by ROI and reinvestment, but constraints limit opportunities.**  
✔ **Real-world investment limits and timing constraints impact valuation.**  

### **Profitability Index (PI) Calculation**
The **Profitability Index (PI)** is a financial metric used to evaluate the profitability of an investment. It measures the value created per dollar invested and is useful when capital is constrained.

### **1. Profitability Index Formula**
\[
PI = \frac{\text{Present Value of Future Cash Flows}}{\text{Initial Investment}}
\]
or equivalently,

\[
PI = \frac{NPV + \text{Initial Investment}}{\text{Initial Investment}}
\]

Where:
- **PI** = Profitability Index
- **NPV** = Net Present Value of the project
- **Initial Investment** = Cost of the project at \( t = 0 \)
- **Present Value of Future Cash Flows** = Discounted value of all future expected cash flows

---

### **2. Decision Rule**
- **PI > 1** → Accept the project (It adds value)
- **PI = 1** → Indifferent (Break-even point)
- **PI < 1** → Reject the project (It destroys value)

---

### **3. Example Calculation**
📌 Suppose a company is evaluating a project with:
- **Initial investment**: $100,000
- **Expected future cash flows**:
  - Year 1: $50,000
  - Year 2: $40,000
  - Year 3: $30,000
- **Discount rate**: 10%

#### **Step 1: Calculate Present Value (PV) of Future Cash Flows**
\[
PV = \frac{50,000}{(1.10)^1} + \frac{40,000}{(1.10)^2} + \frac{30,000}{(1.10)^3}
\]

\[
PV = \frac{50,000}{1.10} + \frac{40,000}{1.21} + \frac{30,000}{1.331}
\]

\[
PV = 45,455 + 33,058 + 22,535 = 101,048
\]

#### **Step 2: Calculate PI**
\[
PI = \frac{101,048}{100,000} = 1.01
\]

🔹 **Interpretation:**  
- Since **PI > 1**, the project is **acceptable** because it generates slightly more value than its cost.

---

### **4. Advantages and Limitations**
✅ **Advantages:**
- Useful for comparing projects, especially when capital is limited.
- Helps rank projects based on value per dollar invested.

❌ **Limitations:**
- **Ignores project size**: A large project with a lower PI may generate more total value than a small project with a high PI.
- **Dependent on accurate cash flow estimation**: Errors in estimating future cash flows can impact PI accuracy.

---

### **Conclusion**
✔ **PI measures the value created per dollar invested.**  
✔ **Projects with PI > 1 should be accepted.**  
✔ **Useful for capital budgeting when resources are limited.**  





### **Cash Flow Pro Forma Analysis for Capital Budgeting**
A **pro forma cash flow analysis** in capital budgeting involves projecting the expected cash inflows and outflows of an investment to assess its profitability. It is essential for evaluating projects using **NPV (Net Present Value), IRR (Internal Rate of Return), and Payback Period**.

---

### **1. Components of a Capital Budgeting Cash Flow Analysis**
The projected cash flows in a **pro forma statement** typically include:

| **Cash Flow Component** | **Formula / Description** |
|-------------------------|--------------------------|
| **Initial Investment (CapEx)** | Upfront cost of equipment, machinery, or new project setup (outflow at \( t = 0 \)). |
| **Operating Cash Inflows** | Revenue generated from the project. |
| **Operating Expenses (OPEX)** | Costs directly associated with the project (materials, labor, maintenance). |
| **Depreciation (Non-Cash Expense)** | Reduces taxable income but is added back in cash flow calculation. |
| **Tax Effects** | Taxes paid on earnings, calculated as **\( EBIT \times (1 - \text{Tax Rate}) \)**. |
| **Net Working Capital (NWC) Changes** | Changes in current assets and liabilities needed to support operations. |
| **Terminal Value (if applicable)** | Salvage value of assets at project end. |

---

### **2. Pro Forma Cash Flow Calculation Steps**
The cash flows for capital budgeting are typically calculated in three stages:

#### **1️⃣ Step 1: Compute Operating Cash Flows (OCF)**
Operating cash flow is derived from earnings before interest and taxes (EBIT) and adjusted for non-cash expenses like depreciation:

\[
\text{OCF} = \text{EBIT} \times (1 - \text{Tax Rate}) + \text{Depreciation}
\]

#### **2️⃣ Step 2: Compute Free Cash Flow (FCF)**
Free cash flow (FCF) accounts for reinvestments in capital assets and working capital.

\[
\text{FCF} = \text{OCF} - \text{Capital Expenditures} - \Delta \text{NWC}
\]

Where:
- \( \Delta \text{NWC} \) is the change in Net Working Capital.

#### **3️⃣ Step 3: Compute Net Present Value (NPV)**
NPV discounts future free cash flows using the required rate of return:

\[
NPV = \sum \frac{FCF_t}{(1 + r)^t} - \text{Initial Investment}
\]

Where:
- \( FCF_t \) = Free Cash Flow in year \( t \)
- \( r \) = Discount rate (cost of capital)
- \( t \) = Year of cash flow

---

### **3. Example: Pro Forma Cash Flow for a New Project**
A company is considering investing in a **new manufacturing plant** with the following assumptions:

- **Initial Investment (CapEx)**: $500,000
- **Project Life**: 5 years
- **Annual Revenue**: $300,000
- **Operating Costs**: $120,000 per year
- **Depreciation (Straight-Line)**: $100,000 per year
- **Tax Rate**: 25%
- **Discount Rate (WACC)**: 10%
- **Net Working Capital Increase**: $20,000 upfront, recovered at the end

#### **📊 Step 1: Calculate EBIT and Operating Cash Flow (OCF)**
\[
EBIT = \text{Revenue} - \text{Operating Costs} - \text{Depreciation}
\]

\[
EBIT = 300,000 - 120,000 - 100,000 = 80,000
\]

\[
\text{After-Tax EBIT} = 80,000 \times (1 - 0.25) = 60,000
\]

\[
\text{OCF} = 60,000 + 100,000 = 160,000
\]

---

#### **📊 Step 2: Compute Free Cash Flows (FCF)**
\[
FCF = OCF - \text{CapEx} - \Delta \text{NWC}
\]

- **Year 0**: Initial investment of **$500,000** and working capital increase of **$20,000** → \( FCF = -520,000 \)
- **Years 1-4**: Constant OCF of **$160,000**, no new CapEx → \( FCF = 160,000 \)
- **Year 5**: OCF of **$160,000** + NWC Recovery of **$20,000** → \( FCF = 180,000 \)

---

#### **📊 Step 3: Compute NPV**
\[
NPV = \sum \frac{FCF_t}{(1.10)^t} - 500,000
\]

Using discounting:

\[
NPV = \frac{160,000}{(1.10)^1} + \frac{160,000}{(1.10)^2} + \frac{160,000}{(1.10)^3} + \frac{160,000}{(1.10)^4} + \frac{180,000}{(1.10)^5} - 500,000
\]

Let's compute the exact NPV:

### **📊 NPV Calculation Result**
\[
NPV = 118,944.31
\]
✔ Since **NPV > 0**, the project **should be accepted** because it creates shareholder value.

---

### **4. Additional Considerations in Pro Forma Analysis**
1. **Sensitivity Analysis**  
   - Vary discount rate, revenue growth, or operating costs to assess risk.

2. **Scenario Analysis**  
   - Best-case vs. worst-case scenarios for revenue and costs.

3. **Terminal Value**  
   - If the project continues indefinitely, include a terminal value estimate.

4. **Break-even Analysis**  
   - Determine the minimum revenue needed to achieve NPV = 0.

---

### **5. Conclusion**
✔ **Pro forma cash flow analysis** is essential for capital budgeting.  
✔ **Operating Cash Flow (OCF)** determines project profitability before investment decisions.  
✔ **Free Cash Flow (FCF)** is used to compute **NPV**, the primary metric for decision-making.  
✔ **Positive NPV** means the project **adds value** and should be accepted.

### **Multi-Stage Dividend Discount Models (DDMs)**  
Multi-stage dividend discount models (DDMs) are used to value stocks when dividends are expected to **grow at different rates** over time. This is useful for companies experiencing high growth initially, followed by stable growth in the long run.

---

## **1. Types of Multi-Stage Dividend Models**
### **1️⃣ Two-Stage Growth Model**  
- **Phase 1:** High, variable dividend growth rate (\( g_1 \)) for a certain period.  
- **Phase 2:** Constant, lower growth rate (\( g_2 \)) after a stable period.  

### **2️⃣ Three-Stage Growth Model**  
- **Phase 1:** Very high initial growth (\( g_1 \)).  
- **Phase 2:** Moderate or declining growth (\( g_2 \)).  
- **Phase 3:** Long-term stable growth (\( g_3 \)).  

---

## **2. Two-Stage Growth Dividend Discount Model**
\[
P_0 = \sum_{t=1}^{n} \frac{D_t}{(1 + r)^t} + \frac{P_n}{(1 + r)^n}
\]
Where:
- \( P_0 \) = Present value of stock price today
- \( D_t \) = Dividend at time \( t \)
- \( r \) = Required rate of return
- \( n \) = End of high-growth phase
- \( P_n \) = Stock price at the start of stable growth phase

\[
P_n = \frac{D_{n+1}}{r - g_2}
\]
Where:
- \( g_2 \) = Stable dividend growth rate
- \( D_{n+1} \) = Dividend at \( n+1 \), calculated as \( D_n(1 + g_2) \)

---

### **Example: Two-Stage Growth Model**
#### **Assumptions**
- Dividend today (\( D_0 \)) = **$2.00**
- High growth rate (\( g_1 \)) = **10%** for **3 years**
- Stable growth rate (\( g_2 \)) = **5%** afterward
- Required return (\( r \)) = **8%**

#### **Step 1: Calculate Dividends for High-Growth Period**
\[
D_1 = D_0 \times (1 + g_1) = 2.00 \times 1.10 = 2.20
\]
\[
D_2 = D_1 \times (1 + g_1) = 2.20 \times 1.10 = 2.42
\]
\[
D_3 = D_2 \times (1 + g_1) = 2.42 \times 1.10 = 2.66
\]

#### **Step 2: Find Stock Price at End of High-Growth Phase (\( P_3 \))**
\[
P_3 = \frac{D_4}{r - g_2} = \frac{D_3 \times (1 + g_2)}{r - g_2}
\]

\[
P_3 = \frac{2.66 \times 1.05}{0.08 - 0.05}
\]

Now, let's compute the actual values.

### **📊 Computed Values**
- **Dividends during high-growth phase:**
  - \( D_1 = 2.20 \)
  - \( D_2 = 2.42 \)
  - \( D_3 = 2.66 \)
- **First dividend after high-growth:**  
  - \( D_4 = 2.80 \) (rounded)
- **Stock price at end of high-growth period:**  
  - \( P_3 = 93.17 \)

---

### **Step 3: Discount Everything to Present Value**
We now discount all cash flows (\( D_1, D_2, D_3, P_3 \)) back to \( P_0 \):

\[
P_0 = \frac{D_1}{(1 + r)^1} + \frac{D_2}{(1 + r)^2} + \frac{D_3}{(1 + r)^3} + \frac{P_3}{(1 + r)^3}
\]

Let's compute the final stock price today.

### **📊 Final Stock Price Today**
\[
P_0 = 80.19
\]

✔ **The intrinsic value of the stock today is $80.19 based on the two-stage growth model.**  

---

### **3. Three-Stage Growth Model**
This model applies when a company goes through:
1. **High growth phase** (\( g_1 \))
2. **Transition phase** (\( g_2 \)) where growth slows down
3. **Stable growth phase** (\( g_3 \))

📌 **Formula:**
\[
P_0 = \sum_{t=1}^{n} \frac{D_t}{(1 + r)^t} + \sum_{t=n+1}^{m} \frac{D_t}{(1 + r)^t} + \frac{P_m}{(1 + r)^m}
\]

- The **transition phase** allows for decreasing growth before reaching long-term stability.
- Used for **growth stocks** that mature over time.



