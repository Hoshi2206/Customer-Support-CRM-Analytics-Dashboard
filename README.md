# Customer-Support-CRM-Analytics-Dashboard
This project provides a comprehensive operational audit of a multi-channel CRM dataset covering 2024–2026. By analyzing 20,000+ support tickets, I identified key performance drivers in resolution efficiency, agent quality, and categorical volume.

<img width="1427" height="983" alt="image" src="https://github.com/user-attachments/assets/7f082430-7458-4c8b-aa6a-7c1575c1ba7e" />

# About the Data
The data used in this analysis is the Customer Support Tickets CRM Dataset, sourced from Kaggle.

This dataset provides a realistic look at customer support operations, featuring over 20,000 ticket records. It includes key operational fields such as:

Ticket Metadata: Ticket IDs, subjects, and issue categories (e.g., Technical, Billing, Fraud).

Operational Metrics: Submission dates, resolution times, and priority levels.

Customer Feedback: Satisfaction scores (1–5 scale).

Agent Performance: Data regarding the assigned support agents and the channel used (Chat, Email, Web Form).

This dataset served as the foundation for the operational audit, allowing for the analysis of trends, agent efficiency, and service quality improvements presented in this project.

# Tech Stack
Tool: Power BI Desktop

Language: DAX (Data Analysis Expressions)

Visuals: Time-series analysis, Matrix performance reporting, and KPI cards.

# Key Findings
- Technical Stability: Even though technical issues have slowly trended downward since early 2025, they’re still our biggest headache, consistently staying above 200 tickets a month. The data also shows some spikes in billing and fraud cases at the end of 2024 and 2025. This signifies these aren't just one-off bugs, but a recurring system issue. The company should really dig into the root cause here and set up better monitoring to catch these holiday-season spikes before they happen.

- Agent Performance: The data shows an interesting trade-off between how many tickets an agent closes and their quality score. While some agents are knocking out a high volume of tickets, others (like Chloe Adams) have slightly lower volume but significantly higher customer satisfaction. It looks like the current setup might be rewarding speed over actually solving the problem. Instead of just pushing for more volume, the company could see much better results by sharing best practices from our top-rated agents across the whole team.

- Channel Efficiency: It’s clear that not all channels are built the same. Web Forms are currently our best channel; they’re the fastest and get the best feedback from customers. Chat and Email, on the other hand, are trailing behind by a few hours in terms of resolution speed. Before we jump to hiring more people, the company should take a closer look at the workflow for Chat and Email. It feels like the tools or the process might be getting in the agents' way, and smoothing that out could make a huge difference in performance.

# Dashboard Features
- Interactive Filtering: Dynamic slicers for Priority, Channel, and Category allow for deep-dive analysis.

- KPI Ribbon: Real-time tracking of Total Ticket Volume, Average Resolution Time, and CSAT %.

- Performance Matrix: Agent performance categorised by both volume and satisfaction to identify top performers and training needs.
