# IT Ticket Analysis – TEJAS K R

---

## 📌 Agenda
```
> PROBLEM STATEMENT  
> DATA DESCRIPTION  
> OBJECTIVE  
> KEY METRICS & VISUALIZATIONS  
> INSIGHTS & RECOMMENDATIONS  
> CONCLUSION
```

---

## 🔍 Problem Statement

The objective is to analyze the IT support ticket management system to:

- Understand agent performance and identify top/bottom performers.
- Assess ticket resolution efficiency and employee satisfaction.
- Pinpoint improvement areas in the process.
- Support staffing decisions like hiring, firing, and training.

---

## 🗂️ Data Description

### 🎫 Tickets Dataset
- **ID** – Unique identifier for each ticket  
- **Ticket Date** – Date when the ticket was raised  
- **Employee ID** – Employee who raised the ticket  
- **Agent ID** – IT agent assigned  
- **Request Category** – e.g., Login Access, System, Software  
- **Issue Type** – IT Error / Request  
- **Severity** – Urgency level  
- **Priority** – Ticket priority  
- **Resolution Time (Days)** – Time taken to resolve the ticket  
- **Satisfaction Rate** – Rated on a scale of 1 to 5

### 👨‍💻 IT Agents Dataset
- **Agent ID**, **Full Name**, **Email**, **Date of Birth (Y-M-D)**

---

## 🎯 Objective

- Analyze ticket trends and volumes over time.
- Measure satisfaction across demographics and time periods.
- Evaluate agent efficiency and resolution times.
- Provide actionable insights for support process improvement.

---

## 📊 Key Metrics & Visualizations

### 1. Tickets Over the Years
- Continuous rise in tickets from 2016 to 2020.
- Major spike between 2019–2020 due to scaling or better reporting.

### 2. Ticket Categories
- **System Issues**: 40% (highest demand)
- **Hardware Issues**: 10% (lowest)

### 3. Satisfaction Over Time
- Improved from **4.0 (2016)** to **4.2 (2020)**.

### 4. Satisfaction by Agent Age Group
- Highest: **Age 48–51 (4.4)**  
- Lowest: **Age 36–39 (3.9)**

### 5. Ticket Distribution by Satisfaction Rate
- **5-star**: 50,770 tickets  
- **4-star**: 27,562 tickets

### 6. Average Resolution Time by Category (Quarter-wise)
- **Hardware**: 7.5–7.7 hrs (longest)  
- **Login Access**: 0.3 hrs (fastest)  
- **Software/System**: Moderate

### 7. Ticket Severity Distribution
- Most common: **Severity 2 (88,656)**  
- Rare: **Severity 0 (356)** and **Severity 4 (1,392)**

### 8. Priority Levels
- Most common: **Priority 3 (35,549)**  
- Least: **Priority 2 (15,845)**

### 9. Ticket Resolution Time Distribution
- Over **25,000 tickets** resolved on same day.
- Delays at 1, 5, and 6 days indicate improvement opportunities.

---

## 💡 Insights & Recommendations

- Automate ticketing & resolution to reduce manual overhead.
- Allocate additional resources during peak periods (Q3 & Q4).
- Train underperforming agents based on satisfaction data.
- Implement self-service tools to reduce volume.
- Regularly track key KPIs for continuous improvement.

---

## ✅ Conclusion

- Ticket volume and demand have grown significantly.
- System issues dominate resource needs.
- Resolution time is efficient but needs tweaks for specific categories.
- Satisfaction levels improving—focus on consistent agent performance.
- Strategic staffing and automation can further improve efficiency and experience.
