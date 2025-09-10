
# 📦 Amazon Sales Data Analysis

## 📑 Dataset Overview
- Source file: `Amazon Sale Report.csv`
- Size: ~128k B2C records and ~871 B2B records.
- Columns analyzed included:
  - **Order & Product details:** Category, Size, Status, Fulfilment, B2B flag, Amount.
  - **Shipping details:** City, Postal code, Country (later dropped for analysis).
  - Other attributes like SKU, ASIN, Courier Status, and Fulfilled-by were removed as non-essential.

## 🧹 Data Cleaning Steps
- Dropped unnecessary columns: `Order ID`, `SKU`, `ship-city`, `ship-postal-code`, `ship-country`, `ASIN`, `Courier Status`, `currency`, `fulfilled-by`.
- Handled missing values by filling `Amount` with **0** where necessary.
- Standardized columns for analysis (e.g., removed `Style` column for simplification).

## 📊 Key Analysis Performed
1. **Order Status Distribution**
   - Visualized counts of each order status (e.g., delivered, cancelled).
2. **Product Sizes**
   - Counted and plotted the frequency of each size ordered.
3. **Fulfilment Methods**
   - Compared fulfilment statuses (e.g., Amazon-fulfilled vs merchant-fulfilled).
4. **B2B vs B2C Sales**
   - B2C orders dominated the dataset (**128,104**), while B2B orders were much fewer (**871**).
5. **Category-Level Insights**
   - Top-performing product categories included **Set**, **Kurta**, and **Western Dresses**.

## 🔍 Key Findings
- **B2C dominates sales**, confirming Amazon’s primary retail model.
- **Category “Set”** generated the highest grossing sales, followed by **Kurta** and **Western Dresses**.
- **Fulfilment analysis** revealed varying performance between Amazon and third-party fulfilment, highlighting potential areas to improve delivery efficiency.
- **Order status distribution** helped identify potential cancellations or delays.
- Size distribution analysis suggests which product sizes are most in demand, guiding inventory planning.

## 🚀 Possible Next Steps
- Perform **time-series analysis** to understand sales trends over months.
- Correlate **category performance** with seasons or events.
- Deep dive into **regional performance** (if location data is retained).
- Build **interactive dashboards** in Power BI or Tableau to visualize these findings.

## 🧭 Practical Recommendations

### 📈 Sales & Marketing
1. **Boost Top Categories:** Focus marketing and inventory on **Set**, **Kurta**, and **Western Dresses**. Use bundles or promotions to increase conversions.
2. **Target B2C Segments:** Prioritize offers and discounts for retail customers while exploring bulk discounts to expand B2B sales.
3. **Personalized Campaigns by Size:** Use size demand patterns to ensure popular sizes are always in stock and tailor marketing accordingly.

### 🚚 Operations & Fulfilment
4. **Optimize Fulfilment Performance:** Evaluate Amazon vs merchant-fulfilled orders for speed and reliability. Allocate high-value products to the better performer.
5. **Reduce Cancellations & Returns:** Identify patterns in cancellations/delays and improve product descriptions or shipping expectations.

### 🧹 Data & Reporting
6. **Automate Dashboards:** Build Power BI dashboards to monitor order status, category sales, and fulfilment in real-time.
7. **Trend Analysis:** Perform time-series analysis to spot seasonal peaks and align campaigns accordingly.

### 📦 Inventory & Resource Planning
8. **Inventory Forecasting:** Forecast demand using category and size insights to optimize stock levels.
9. **Regional Strategy:** If location data is available, tailor inventory and marketing to regions with the highest sales.

### 🌟 Customer Experience
10. **Customer Retention Programs:** Launch loyalty or referral programs and proactively address complaints to boost satisfaction.
