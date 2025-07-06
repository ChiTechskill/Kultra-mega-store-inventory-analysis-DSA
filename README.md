# Kultra-mega-store-inventory-analysis-DSA
- **Insight**: These customers could be targeted for upselling through tailored offers, onboarding campaigns, or customer service interventions to increase their lifetime value.

### 🔹 5. Shipping Method with the Highest Total Cost
- Shipping costs were aggregated by shipping mode.
- **Insight**: **Express Air** emerged as the most expensive shipping method. While it may offer faster delivery, its cost-effectiveness should be reassessed, especially for low-priority orders.

### 🔹 6. Most Valuable Customers & What They Buy
- Customers with the **highest total sales** were extracted along with the products they typically purchase.
- **Insight**: These high-value clients are important to retain. They often buy high-margin or frequently sold items, suggesting opportunities for bundling or loyalty incentives.

### 🔹 7. Top Small Business Customer
- The highest-spending **Small Business** customer was identified.
- **Insight**: This shows strong engagement from small business clients, warranting dedicated B2B offerings or relationship management.

### 🔹 8. Most Active Corporate Customer
- The **Corporate** customer with the **most orders** placed between 2009–2012 was extracted.
- **Insight**: Regular ordering indicates a stable B2B relationship. Consider special discounts or account-based marketing to maintain this loyalty.

### 🔹 9. Most Profitable Consumer
- The **Consumer** segment’s most profitable customer was determined using total profit generated.
- **Insight**: This customer could be studied for their purchasing habits and targeted with exclusive deals or referral programs.

### 🔹 10. Returned Orders and Segmentation
- Joined with the `Order_Status` table to identify customers who returned items.
- **Insight**: Returns came mostly from customers in a specific segment (e.g., Consumer or Small Business). This could point to issues with expectations, delivery delays, or product quality.

### 🔹 11. Are Shipping Costs Aligned with Order Priority?
- Shipping cost and mode were analyzed in relation to **Order Priority**.
- **Insight**: Some **low-priority orders were shipped using costly methods like Express Air**, which is inefficient. High-priority orders sometimes used slower shipping.
- **Recommendation**: Enforce shipping policies that align delivery method with priority:
  - **Express Air** for "Critical"/"High"
  - **Delivery Truck** for "Low" or "Not Specified"

---

## ✅ Final Recommendations

1. **Target low-value customers** with promotional strategies to drive revenue.
2. **Align shipping methods with order urgency** to reduce operational costs.
3. **Leverage top-performing customers and products** with loyalty incentives.
4. **Investigate reasons behind returns** in specific segments or product lines.
5. **Expand market efforts** in underperforming regions with growth potential.
