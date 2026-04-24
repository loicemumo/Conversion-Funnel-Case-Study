## From 472K Visits to 32K Purchases: A Conversion Funnel Case Study

---

## Context

The toy e-commerce retailer was driving significant traffic but lacked visibility into where users were dropping off and which acquisition channels and devices were actually converting. The goal was to identify funnel inefficiencies and optimize conversion performance across channels, devices, and product interactions.

---

## Approach

* Cleaned and structured ~500K session-level web logs using Python (Pandas, NumPy)
* Standardized 7-step customer journey funnel across multiple page variants
* Mapped sessions to conversion stages using page-level aggregation
* Built funnel progression metrics and conversion rates across stages, channels, and devices
* Segmented performance by traffic source (Google vs Bing), campaign type (brand vs non-brand), and device type

---

## Key Findings

* Only **6.8% of sessions convert to purchase**, indicating major funnel inefficiency
* The **Cart stage is the largest drop-off point (54.8% exit rate)**, representing the most critical conversion leak
* **Bing outperforms Google in conversion rate (7.19% vs. 6.75%)** despite lower traffic share
* **Brand campaigns significantly outperform non-brand campaigns** across both search engines
* **Desktop converts nearly 3× better than mobile (8.50% vs. 3.09%)**, despite mobile driving nearly a third of traffic
* The *Forever Love Bear* launch improved **product-to-cart conversion by +11.7%**, indicating strong product-led engagement impact

---

## Recommendations

* Reduce friction in the cart and checkout flow to address the primary abandonment point
* Optimize mobile checkout experience to close the major desktop–mobile conversion gap
* Reallocate paid search spend toward Bing and high-performing branded campaigns
* Strengthen product-led funnel strategy by replicating successful launch patterns
* Standardize and simplify legacy funnel page variants to reduce user fragmentation
* Improve product page engagement and progression into cart through clearer CTAs and value framing

---

## Tools

Python (Pandas, NumPy), Matplotlib, Seaborn, Plotly
