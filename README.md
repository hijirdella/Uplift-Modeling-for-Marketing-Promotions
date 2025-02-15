---

## **Uplift Modeling: Discount vs. Buy One Get One (BOGO) 📊**  
### **Optimizing Marketing Promotions with Uplift Analysis**  

### **📌 Project Overview**  
This project explores **Uplift Modeling** to measure the impact of two marketing offers:  
1. **Discount** (Treatment: Discount, Control: No Offer)  
2. **Buy One Get One (BOGO)** (Treatment: BOGO, Control: No Offer)  

The goal is to identify **persuadable customers**, optimize targeting, and maximize conversion rates while minimizing marketing waste.  

--

### **🔍 Key Insights & Findings**  
#### **Offer Effectiveness**  
| **Metric**                    | **Discount (Case A)** | **BOGO (Case B)** |
|--------------------------------|----------------------|-------------------|
| **Total Conversions (Treated)** | **1,877**           | **1,450**        |
| **Total Conversions (Control)** | **1,144**           | **1,135**        |
| **Net Uplift**                  | **+733**            | **+315**         |
| **Negative Uplift Impact**       | **-0.198**          | **-0.217**       |

- **Discount had a higher uplift than BOGO**, leading to more conversions.  
- **BOGO showed positive uplift**, but it was **less effective than Discount**.  
- **Negative uplift was observed in both cases**, meaning some customers reacted negatively to the offer.  

#### **Model Performance**  
| **Model**                   | **AUUC (Discount)** | **AUUC (BOGO)** |
|-----------------------------|---------------------|-----------------|
| **S-Learner**               | **0.523**           | **0.502**       |
| **Uplift Random Forest**    | **0.477**           | **0.509**       |

- **S-Learner performed better for Discount**, making it the best choice for uplift modeling in this case.  
- **Uplift Random Forest performed slightly better for BOGO**, but its performance was inconsistent.  

---

### **🛠️ Models & Techniques Used**  
- **Uplift Modeling Approaches:**
  - **S-Learner** (Meta-Learner using LightGBM)  
  - **Uplift Random Forest**  
- **Evaluation Metrics:**  
  - **AUUC (Area Under Uplift Curve)**  
  - **Gain Charts for Treatment Effectiveness**  
- **Feature Engineering & Segmentation:**  
  - Customer behavior analysis (Recency, Purchase History, Referral Impact)  
  - One-hot encoding for categorical variables  

---

### **📈 Business Recommendations**  
✔ **Prioritize Discount over BOGO** for promotions, as it led to **733 more conversions** compared to **315 from BOGO**.  
✔ **Use S-Learner for Discount campaigns**, as it outperformed Uplift Random Forest (**AUUC: 0.523 vs. 0.477**).  
✔ **Improve segmentation** to avoid targeting customers with negative uplift scores (-0.198 for Discount, -0.217 for BOGO).  
✔ **Test alternative uplift models** (e.g., Uplift Tree, T-Learner) to enhance prediction accuracy.  

---


### **📢 Quote on Uplift Modeling**  
> *"Marketing is not just about reaching customers—it's about reaching the right customers. Uplift modeling transforms promotions from guesswork into precision, ensuring every dollar spent moves the needle where it truly matters."*  

---

### **📌 Author & Contributions**  
👤 **Hijir Della Wirasti**  
Feel free to contribute, report issues, or suggest improvements! 🚀  

---

### **📬 Contact & Connect**  
📧 **Email**: [hijirdw@gmail.com](mailto:hijirdw@gmail.com)  
🔗 **LinkedIn**: [Hijir Della Wirasti](https://www.linkedin.com/in/hijirdella/)  

---
