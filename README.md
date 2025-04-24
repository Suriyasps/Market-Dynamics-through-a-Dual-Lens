# Market Dynamics through a Dual Lens: Conjoint Analysis and PCA

# Marketing Analytics  
**Project By**: Suriya Subbiah Perumal  

---

## 📌 Overview

This project employs **Conjoint Analysis** and **Principal Component Analysis (PCA)** to uncover actionable insights into customer preferences and perceptions for a new product. Through a combination of fractional factorial design and perceptual mapping, the study provides strategic guidance for **product design, pricing, and segmentation**.

---

## 🧭 Methodology

### 🧩 Conjoint Analysis
- **Purpose**: Estimate consumer **part-worth utilities**, attribute importance, and **willingness to pay (WTP)**.
- **Design**: 18 profiles created from 6 attributes (levels: 3, 3, 3, 3, 2, 2) via **fractional factorial design**.
- **Analysis**: Part-worths, attribute importance, and WTP computed.
- **Tooling**: R with `conjoint` and `ggplot2`; visualization in Tableau.

### 📈 PCA (Principal Component Analysis)
- **Dataset**: Ratings on 32 product models based on 11 features.
- **Goal**: Dimensionality reduction and **perceptual mapping**.
- **Output**: Loadings, explained variance, and model positioning along key dimensions.

---

## 🔍 Conjoint Analysis Highlights

### 🔢 Why 18 Product Profiles?
- Reduces survey fatigue while preserving orthogonal attribute representation.
- Trades off exhaustive coverage for respondent engagement and statistical clarity.

### ⚙️ Attribute Insights
- **Most valued**: Price, Service Level, Environmental Friendliness.
- **Least valued**: Marketing Proficiency.

### 💰 Willingness to Pay (WTP)
- Most attributes received **negative WTP** — suggesting consumer expectations are below the base price.
- **Highest resistance**: “Higher than Market Average” quality materials.

### 🎯 Market Segmentation via Conjoint
- **Segments consumers** by preferences and sensitivities (e.g., price-sensitive vs. eco-conscious).
- Informs benefit segmentation and differentiated pricing.

---

## 📊 PCA & Perceptual Mapping

### Key Insights:
- **Factor 1** loaded heavily on Feature2, Feature3, and Feature6.
- **Factor 2** revealed importance of Feature7 and Feature10.
- Models placed near certain features suggest consumer associations.

### Considerations:
- PCA simplifies complexity but may **overlook nuanced behavior**.
- The perceptual map offers a static snapshot — requires regular validation.

---

## 🔬 Critical Analysis

- Clear **attitude-behavior gap**: customers support green attributes but resist paying for them.
- **Price and service** drive decisions more than brand messaging.
- Companies should re-evaluate how they market quality and sustainability.
- Consideration for **hybrid conjoint designs** or **adaptive models** in future.

---

## 🛠 Tools & Techniques Used

- **R Libraries**: `conjoint`, `data.table`, `ggplot2`
- **Survey Data**: Fractional factorial profiles + preference rankings
- **Visualization**: Tableau for perceptual maps & utility plots
- **PCA Outputs**: Singular values, variance explained, factor loadings

---

## ✅ Conclusion

- **Conjoint analysis** effectively captured attribute preferences, enabling **segmentation** and **value-based pricing** strategies.
- **PCA** provided dimensional clarity for **brand positioning** and model evaluation.
- While findings are insightful, future iterations should incorporate **qualitative inputs**, **dynamic segmentation**, and possibly LLM-enhanced feedback analysis.

---

## 📚 References

- Green & Srinivasan (1990), Orme (2006) – Conjoint Design
- Luchs et al. (2010), Kahneman & Tversky (2013) – Behavioral Economics
- Malhotra (2020), Hair et al. (2009) – Multivariate Analysis
- Carrington et al. (2010), Wind (1978) – Segmentation Theory

---

## 🔄 Future Work

- Integrate **consumer sentiment data** using **LLM-powered NLP**.
- Use **adaptive conjoint analysis (ACA)** for real-time profile adjustments.
- Expand PCA to dynamic market models or factor-rotation for behavioral clustering.

