# Simple Survey Analysis & Feedback Dashboard

<img width="1834" height="707" alt="Screenshot 2025-08-02 110627" src="https://github.com/user-attachments/assets/bd99cd14-b88b-4a9e-bac3-0adf2f54f87b" />

## Overview

This Excel-based template is designed to **analyze survey responses and feedback** with a clean, interactive, and organized dashboard. It helps teams gain insights from customer or user feedback without complex tools — perfect for:

- Customer satisfaction surveys  
- Product or service feedback  
- Internal team surveys or HR evaluations  
- Event/campaign feedback forms  

---

## ✨ Key Features

- ✅ **User-friendly interface** – Clear layout with visual hierarchy and logical flow  
- ✅ **Pivot Table engine** – Fast, formula-free summary tables that update instantly  
- ✅ **Sentiment analysis** – Auto-generated sentiment scores from comments using a custom keyword list  
- ✅ **Tagging system** – Responses tagged as Positive, Neutral, or Negative based on tone  
- ✅ **KPI Cards** – High-level stats: Total Responses, Avg. Rating, % Positive/Neutral/Negative  
- ✅ **Dynamic charts** – Visuals for sentiment, ratings, region, and feedback channel  
- ✅ **Refreshable & scalable** – Easily add new data and refresh all outputs  

---

## 🗂️ Sheets Overview

### 1. `Survey Data`  
Stores all raw feedback and metadata fields. This is where new survey records are entered or imported.

**Columns include:**
- Respondent ID  
- Submission Date  
- Age Group  
- Gender  
- Region  
- Channel  
- Question Category  
- Question  
- Response  
- Rating (1–5)  
- Comment  
- Tag (auto-assigned)  
- Sentiment Score (auto-calculated)

---

### 2. `Sentiment Keywords`  
Helper sheet used for keyword-based sentiment scoring. Includes:

- Column A: Positive words  
- Column B: Negative words  
- Column C (optional): Suggestive/neutral words  

Used in formulas to calculate a sentiment score ranging from **-1 to +1**.

---

### 3. `Summary & Insights`  
The main dashboard and analysis sheet. Powered by Pivot Tables and visual charts.

**Visuals and metrics include:**
- **📌 KPI Cards**:  
  - Total Responses  
  - Average Rating  
  - % Positive Feedback  
  - % Neutral Feedback  
  - % Negative Feedback  
  - Average Sentiment Score  

- **📊 Charts:**  
  - Pie Chart: Sentiment Breakdown  
  - Column Chart: Rating Distribution (1 to 5)   
  - Pie/Bar Chart: Top Feedback Channels  

---

## 📌 Bonus Functionalities

- **Sentiment Score Normalization:**  
  Formula scales score to a range of -1 to +1 for consistency across comments.

- **Tag Automation:**  
  Each comment is auto-tagged using simple logic:  
  - `> 0.5` → Positive  
  - `0 to 0.5` → Neutral  
  - `< 0` → Negative

## 🔄 Workflow

1. Fill in or import survey responses into the `Survey Data` sheet  
2. Add keywords (or edit) in the `Sentiment Keywords` sheet  
3. Refresh Pivot Tables on the `Summary & Insights` sheet  
4. Get instant visuals, summaries, and insights

---

## ✅ Requirements

- Microsoft Excel 2013 or later  
- No add-ins or macros required  
- Works offline  
- Beginner-friendly

---

## 📦 File Contents

| File/Sheet               | Purpose                        |
|--------------------------|--------------------------------|
| `Survey Data`            | Raw data storage               |
| `Sentiment Keywords`     | Keyword dictionary for scoring |
| `Summary & Insights`     | Dashboard & visual analytics   |

---

## 🧠 Example Use Cases

- A marketing team evaluating customer satisfaction after a product launch  
- HR analyzing internal employee surveys across departments  
- Customer service team tracking feedback channels and delivery issues  
- Product team understanding trends in complaints or praise over time

---

