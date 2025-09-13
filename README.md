# Weather-Based Operations Automation

## Business Problem
A beachside kiosk's sales and staffing needs are heavily influenced by Miami's volatile weather. The manual process of checking forecasts is inefficient and often leads to reactive decisions, resulting in over/understaffing, wasted inventory, and missed sales opportunities when weather conditions change unexpectedly.

## Solution Overview
This project provides an intelligent automation that acts as a daily operations assistant. Every morning, the workflow automatically fetches the real-time Miami weather forecast using a Webhook. It then feeds this data to a Google Gemini AI agent, which uses a structured prompt to interpret the forecast and generate a custom operational plan. This plan, which includes product focus, staffing suggestions, and marketing messages, is emailed directly to the manager, enabling proactive, data-driven decisions.

## Tools Used
* **Zapier:** The core automation platform used to build and manage the workflow.
* **Webhooks:** Used to make a GET request to an external weather API.
* **Google Gemini AI:** The AI engine for interpreting weather data and generating a strategic plan.
* **Gmail:** Used to deliver the daily operational plan to the kiosk manager.

## Workflow Diagram

<!-- 
********************************************************************************
<img width="534" height="726" alt="image" src="https://github.com/user-attachments/assets/cb148073-bbd7-4c38-aded-bc2399e8dc3b" />

********************************************************************************
-->
![Workflow Diagram for Weather Automation][https://github.com/user-attachments/assets/cb148073-bbd7-4c38-aded-bc2399e8dc3b]

## Key Features & Results
-   **Automated Data Fetching:** Utilized Webhooks to automatically fetch real-time weather data from an external API, providing a reliable data source for decision-making.
-   **AI-Driven Strategy:** Deployed a Gemini AI agent with a structured prompt to interpret weather data and generate strategic recommendations for product focus, staffing, and marketing.
-   **Risk Management:** Implemented conditional paths to automatically escalate alerts for severe weather, enabling proactive risk management and ensuring business continuity.

## Business Value
This automated system delivers tangible business value by transforming a manual task into a strategic asset.
-   **Increased Efficiency & Sales:** Saves the manager's time and helps optimize product offerings based on weather, maximizing revenue.
-   **Reduced Labor Costs:** Provides data-driven staffing suggestions to prevent overstaffing on slow days.
-   **Proactive Risk Management:** The severe weather alert system gives advance notice to take necessary precautions, protecting assets and ensuring safety.
