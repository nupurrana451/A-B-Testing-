# 🛍️ Nuri: A Fashion Brand – A/B Testing Analysis

## 📌 Problem Statement
Nuri is a fashion brand with a wide range of apparels available on its website. The brand has been facing challenges with **customer retention** and wanted to test a new campaign designed to increase the number of users progressing to the **checkout stage** of their funnel.  

A **month-long A/B test** was conducted with two groups:  

- **Test group** → Users exposed to new advertisements featuring Nuri’s best-selling item.  
- **Control group** → Users not exposed to the new advertisements.  

The customer funnel being optimized:  View Home Page → Explore Clothes (Search) → Add to Cart → Checkout


The goal was to establish the **success or failure of the campaign** by comparing KPIs between the test and control groups.  

---

## 📊 Key Findings

### Primary Metrics (Success Criteria)
- **CTR ↑ 104.5%** → New ads attracted significantly more clicks.  
- **Purchase Rate ↑ 71.4%** → More users who entered the funnel ended up purchasing.  

✅ Indicates **positive campaign impact** on engagement and conversions.  

---

### Guardrail Metrics (Health/Cost Checks)
- **Add-to-Cart Rate ↓ 43.3%** → Users less engaged at the cart stage.  
- **Cost Per Acquisition (CPA) ↑ 18.8%** → Acquisitions became more expensive.  
- **Search Rate ↓ 0.2%** → Negligible change.  
- **Checkout Rate ↑ 33.7%** → Strong improvement once users entered checkout.  

⚠️ Indicates **risks to funnel health and cost efficiency** despite top-line gains.  

---

## ✅ Conclusion
The test campaign **succeeded in driving traffic and purchases** but failed on certain **guardrail metrics**:  
- Cost efficiency worsened (higher CPA).  
- Funnel health weakened at the Add-to-Cart stage.  

This means the campaign, while promising, **cannot be scaled confidently without further optimization**.  

---

## 💡 Recommendations
1. **Guardrail Monitoring**  
   - Treat **CPA** and **Add-to-Cart rate** as critical guardrails before full rollout.  

2. **Optimize Cart Engagement**  
   - Investigate cart-stage drop-offs (pricing clarity, UX, friction points).  
   - Test incentives such as promo codes, shipping offers, or cart reminders.  

3. **Improve Cost Efficiency**  
   - Refine targeting to high-intent segments.  
   - A/B test creatives/placements to reduce CPC and CPA.  

4. **Validate Funnel Dynamics**  
   - If users are bypassing cart via **fast checkout**, adjust measurement to avoid misleading cart-rate drops.  

5. **Iterative Testing**  
   - Run a second campaign incorporating optimizations to validate guardrails before scaling.  

---

## 🚀 Tech Stack
- **Python** → pandas, numpy, scipy, matplotlib, seaborn  
- **Statistical Testing** → Shapiro-Wilk, Levene’s test, Student/Welch t-tests, Mann-Whitney U  
- **Effect Size** → Cliff’s Delta  
- **Visualization** → ECDF plots, histograms, QQ plots  

---

## 📌 Author
👩‍💻 Analysis by *[Nupur Rana]*  
