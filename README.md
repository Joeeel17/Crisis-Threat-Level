README.md

# 🛡️ Crisis Threat Level Framework
A dynamic, Excel-based system designed to help crisis teams gauge the severity of a potential or ongoing issue in real time. This framework combines multiple metrics — virality, conversation volume, and sentiment — into a single, actionable threat level that supports timely decision-making and client reporting.

## 📌 Problem Statement

Crisis monitoring teams often rely on separate metrics such as engagements and mentions. While informative, these isolated figures do not offer a unified, time-sensitive view of how severe a threat truly is — nor what action should be taken.

This framework addresses:
- ❗ Lack of a concise, standardized threat severity metric
- ⏱️ Need for time-sensitive tracking (especially as engagements can spike rapidly, e.g., 30M+ views)
- 📊 Desire for a transparent and justifiable breakdown that supports escalation decisions

---

## 👤 Role & Contribution

As the lead analyst and framework developer, I:

- 🔧 Developed a threat metric to monitor crises in real time
- 📈 Defined a *crisis* as any issue generating (or potentially generating) negative brand-related chatter online
- 🧮 Incorporated core indicators:
  - **Virality** (Engagements)
  - **Conversation Volume** (Mentions)
  - **Sentiment** (Net sentiment score from positive, neutral, and negative posts)
- 🧪 Prototyped and tested different scoring models (mean, median, weighted approaches)
- 📊 Designed an Excel-based dashboard for real-time data entry and automated threat scoring

---

## ⚙️ How It Works

This framework enables crisis teams to:

1. Input daily or hourly social data (manually or via internal tools)
2. Automatically calculate a composite threat level score
3. View visual breakdowns that guide client response recommendations

> 🔍 The repository includes **fictional data** to illustrate how the metric works in practice.

---

## 📂 Repository Contents

| File/Folder | Description |
|-------------|-------------|
| `Threat-Level-Template.xlsx` | Excel file with working threat level system, dummy data, and formulas |
| `Use-Case-Example.md`       | Fictional scenario showing how the framework applies to a simulated crisis |
| `assets/`                   | Supporting visuals such as framework diagrams and screenshots |
| `README.md`                 | Project overview |

---

## 📝 Example Use Case

A fictional use case has been included to demonstrate how a typical crisis scenario is assessed using the framework.

📄 [See the example →](./Use-Case-Example.md)



---

## 🚫 Disclaimer

This framework is intended solely for **portfolio and demonstration** purposes.  
All data and scenarios in this repository are **fictional**. No proprietary, client, or confidential company information is included.


---

## 🔮 Future Enhancements

- Real-time integration with social media monitoring tools (via APIs)
- Web dashboard version for broader accessibility
- Industry-specific threshold presets for different risk sensitivities
