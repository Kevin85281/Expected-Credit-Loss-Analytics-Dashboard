# Expected-Credit-Loss-Analytics-Dashboard

Overview

This project explores how credit risk behaves in real portfolios rather than in theory. It demonstrates an end to end Expected Credit Loss framework that connects loan level characteristics to portfolio level outcomes under multiple economic scenarios.

What This Project Shows

Credit risk is not just PD, LGD, and a formula. When real borrowers, regions, and industries are involved, risk shifts in ways that static models cannot explain on their own. This dashboard translates raw exposure data into a view that helps stakeholders understand where loss is coming from and how it evolves under stress.

Key Analytical Components

Loan Level Risk Segmentation
Breakdowns by FICO bucket, geography, industry, and loan purpose reveal where vulnerability concentrates.

Scenario Based Modeling
Base, Adverse, and Severely Adverse scenarios highlight how losses respond to economic stress rather than balance growth.

Portfolio Rollups
Loan level calculations dynamically aggregate into portfolio ECL, allowing comparison across segments and scenarios.

Risk Sensitivity Analysis
The dashboard surfaces how certain regions and borrower profiles react more sharply during downturn conditions.

Insights Observed

Lower FICO segments generated disproportionate Expected Credit Loss even when exposure was smaller.
Some regions showed significantly higher sensitivity under stress scenarios, indicating localized economic dependence.
ECL rates increased sharply in the Severely Adverse scenario while total exposure remained relatively stable, signaling that risk can accelerate faster than balance sheet growth.
Portfolio composition mattered as much as portfolio size.

Tools and Methods

Power BI for data modeling, visualization, and interactive analysis
SQL for data preparation and transformation
Structured data cleaning to align loan level attributes with scenario inputs
Analytical modeling support to connect credit metrics with business context

Why It Matters

Financial institutions often monitor exposure growth but miss how quickly underlying risk can change. This solution focuses on explaining why a metric moved, not just reporting that it moved. It helps translate model outputs into decisions around underwriting, concentration risk, and stress preparedness.

Experience Reflected in This Work

Over several years working across data preparation, modeling support, dashboard development, and stakeholder reporting, the focus has remained consistent. Connect analytics to real portfolio behavior. Make risk interpretable. Deliver insights that can guide action rather than sit in a report.
