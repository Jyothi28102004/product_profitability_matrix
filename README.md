# 📊 Product Profitability Matrix

**Tools Used**: Python (Plotly, Seaborn, Pandas), Excel, Power BI / Tableau  
**Dataset**: Real-world retail SKU sales data (includes profit, cost, units sold, price, discount, and promo info)

---

## 📌 Objective

Identify high-volume, low-profit SKUs and recommend pricing changes to improve profitability.

> 🎯 **Goal**:  
Analyze profit vs units sold for all SKUs and recommend pricing adjustments for products that sell well but underperform financially.

---

## 🧠 Business Questions Answered

- Which fast-selling products are least profitable?
- Are certain brands or categories consistently low-margin?
- What pricing or promotional actions can boost margins?

---

## 🛠️ Tools & Technologies

| Category            | Tools Used                                 |
|---------------------|-------------------------------------       |
| Language            | Python 3.10                                |
| Libraries           | `Pandas`, `Plotly`, `Seaborn`, `Matplotlib` 
| Visualization       | Power BI / Tableau _(optional)_            |
| Platform            | Google Colab, GitHub                       |
| File Types          | `.csv`, `.ipynb`, `.md`                    |

---

## 📦 Dataset Source

This project uses a real-world retail dataset:

> **Dunnhumby – The Complete Journey**  
> 🏪 Transactional data from a US grocery chain  
> 📥 Download from Kaggle: [frtgnn/dunnhumby-the-complete-journey](https://www.kaggle.com/datasets/frtgnn/dunnhumby-the-complete-journey)

### ✅ Description:
- Household-level transactions with `product_id`, `quantity`, `sales_value`, `retail_disc`, `coupon_disc`, `trans_time`
- Product metadata: `brand`, `commodity_desc`, `subcategory`
- Coupon and campaign data for promotional analysis
- Perfect for **real-time**, **real-life**, **5⭐ advanced analytics**, including:
  - Product profitability modeling
  - Sales and promotion impact
  - Price elasticity and discount effectiveness

---

## 📂 Dataset Structure

Raw CSV files included:
- `transaction_data.csv`  
- `product.csv`  
- `coupon.csv`  
- `coupon_redempt.csv`  
- `hh_demographic.csv`  
- `campaign_table.csv`  
- `campaign_desc.csv`  
- `campaign_coupon.csv`

---

## 📈 Project Workflow

| Phase | Description |
|-------|-------------|
| ✅ Phase 1 | Upload & Load CSVs (Google Colab) |
| ✅ Phase 2 | Clean & Prepare Data |
| ✅ Phase 3 | Calculate SKU Profitability |
| ✅ Phase 4 | Plot Units vs Profit (Interactive) |
| ✅ Phase 5 | Flag High-Volume, Low-Margin SKUs |
| ✅ Phase 6 | Generate Pricing Recommendations |
| ✅ Phase 7 | Build Dashboard (Plotly + Table) |
| ✅ Phase 8 | Root Cause Analysis & Heatmaps |

---

## 📌 Key Features

- Interactive Plotly visualizations for quick insights
- Root-cause heatmaps for deeper analysis
- Exportable CSV with clear pricing actions
- Professional business dashboard (colab + BI-ready visuals)

---


---

## 📌 Sample Output

| product_id | brand | quantity | profit | profit_margin | pricing_recommendation       |
|------------|-------|----------|--------|----------------|------------------------------|
| P1234      | ACME  | 5,000    | $20    | 0.4%           | Increase Price               |
| P5678      | Dell  | 7,000    | $35    | 0.5%           | Review Promotional Strategy |

---

## 📌 Visual Snapshots

- 📍 Units vs Profit scatter  
- 🔥 Brand × Category heatmap  
- 🥧 Pie chart: recommendation distribution  
- 🧾 Detailed SKU recommendation table  

(_Visuals are in `/visuals` folder; include PNGs in final README_)

---

## 🧠 Strategic Insights

- **💸 Margin Erosion**: Several high-volume SKUs operate below 1% margin.
- **🔥 Brand Focus**: 3 brands have systemic low-margin issues.
- **🎯 Action Plan**: Increase prices or reduce discount depth on ~40 flagged SKUs.

---

## 🚀 Future Enhancements

- Add time-series forecasting for trend analysis
- Integrate dynamic pricing using APIs
- Deploy dashboard as a web app via Streamlit or Dash

---

## 🧑‍💻 Author

Author Jyothi Bhaskar Vardhi 
LinkedIn: www.linkedin.com/in/jyothivardhi 
GitHub: Jyothi28102004


