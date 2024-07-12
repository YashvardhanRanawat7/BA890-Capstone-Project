# Heron AI Capstone Project
**Business Advisors:** Daphne Pariser (CEO) , Julien Pinede (CTO) <br>
**Team Members:** Dylan Kakkanad, Pritam Pandit, Sulaiman Alhomoud ,Yashvardhan Ranawat <br>

## Problem Statement 
We are currently working on mainly two problems 
* **Business Snapshot Dashboard:**<br>
We are developing a comprehensive business dashboard for QuickBooks customers. This dashboard will provide a snapshot of the company's financial health, cash flow, sales performance, customer insights, expense breakdown, and operational metrics. The aim is to leverage data from various sources using the Unified API to deliver valuable insights and facilitate informed decision-making.
* **Strategic Dashboard Blueprint:**<br>
Construct a diverse array of pre-built dashboard layouts informed by user insights and soft launch data. This approach ensures template designs are tailored to meet specific user requirements and industry preferences, incorporating multi-chart configurations based on thorough market analysis.

## Scope 
Develop a comprehensive business dashboard for QuickBooks customers, 

*   integrating financial and operational data via mapping to the API.
*   Create modules for financial health, cash flow, sales, customer insights, expenses, and operational metrics.
*   Design an intuitive, customizable user interface with responsive design.
*   Construct a diverse array of pre-built dashboard layouts based on user insights and market analysis.
*   Implement data integration, security measures, and performance optimization.
*   Conduct thorough testing, create documentation, and establish ongoing support and maintenance processes.

## Approach
**Business Snapshot Dashboard:** <br>
Our approach to this project is broken down into the following steps:<br>
* Understanding the backend and frontend codebase: Conducted a comprehensive examination of the existing codebase, focusing on both backend and frontend components. This involved analyzing the architecture of current dashboards and chatbots, studying the data flow, and identifying key integration points. The goal was to ensure our new developments would seamlessly integrate with the established infrastructure, maintaining consistency and avoiding disruptions to existing functionalities.
* Understanding proprietary health score calculations: To gain a comprehensive understanding of the 'Health Score' calculations, we utilized a set of dummy data and developed a Python script to execute these calculations. This approach allowed us to replicate and analyze the calculation process in detail, ensuring a thorough comprehension of the methodology used.
* Working with Unified API: Our subsequent step involved mapping the data required for the calculations to the Unified API. We then fetched data from the Unified API, saving information from various objects such as invoices, transactions, and employees into CSV or JSON files. After securing the data, we performed the relevant calculations to populate the dashboard accurately.
* Visualizations on front-end: Expanded the frontend's visual capabilities by introducing new chart types, such as gauge meters, to represent complex data in an intuitive manner. Simultaneously, we leveraged existing ReactJS components to maintain consistency with the current design language. This dual approach of introducing new visualizations while optimizing existing ones ensured a rich, informative, and cohesive user interface for the dashboard.

**Strategic Dashboard Blueprint:**<br>
Our approach to this project is broken down into the following steps:<br>
* Researching Dashboards and Reports: Conducted comprehensive research on the most frequently used dashboards and reports in the accounting space, analyzing each for its benefits, outcomes, applicability, and possible chart visualizations. Our detailed report examined how each dashboard could improve financial visibility and decision-making, its expected impact on business performance, which types of businesses would find it most useful, and the most effective ways to visually represent the data. This thorough analysis provides users with valuable insights for selecting and implementing QuickBooks dashboard templates, enabling them to make informed decisions and maximize the benefits of their chosen financial tools.
* Mapping Dashboard Templates to QuickBooks API: We carefully mapped all QuickBooks dashboard templates to the QuickBooks API, ensuring smooth integration with the existing QuickBooks system. This involved reviewing current templates, studying the API documentation, and creating a detailed mapping plan. We developed templates for integration scripts, which would be used to fetch and process API data, ensuring accurate and up-to-date dashboard information. After thorough testing and adjustments, we documented the entire process for future reference. This comprehensive approach resulted in a reliable integration solution that enhances data visualization and analysis capabilities within QuickBooks.
* Developed 10+ Dashboard Templates with Graphs and Calculations: Built over 10 dashboard templates featuring various graphs and calculations to meet the diverse needs of accounting and fintech companies. These templates provided clear, actionable insights and covered key financial indicators, performance metrics, and trend analyses. Designed with user-friendly interfaces and customizable options, they catered to financial analysts, accountants, executives, and decision-makers. Extensive testing and user feedback ensured their accuracy, reliability, and usability, resulting in robust tools that significantly improved data-driven decision-making processes.
* Expanding and Re-Mapping Dashboards to Unified API: Re-mapped and expanded multiple existing dashboard templates to the Unified API to meet industry needs. This involved reviewing and adapting the existing templates for compatibility with the Unified API, creating detailed mappings for data integration, and developing new dashboard components that align with updated requirements. This process ensured that the dashboards utilized the Unified API effectively, providing enhanced data visualization and analysis capabilities for a broad range of accounting and fintech applications.
* Developing Financial Report Templates: Developed an expanded financial report template with sample numbers for use in the testing phase. This template was designed to facilitate thorough testing and ensure the reliability of our dashboards and reports.

## Initial Data Analysis
Our project does not entail ‘analyzing’ any data however it does entail figuring out which metrics a company should be looking at to get a sense of their financial performance. For this we did a thorough analysis of existing dashboards and solutions that exist on the market and came up with the most useful ones.

## Expected Findings 
* Improved Decision-Making: Comprehensive financial and operational insights enabling faster, data-driven decisions.
* Efficient Data Integration: Seamless data consolidation from various sources via the Unified API.
* Enhanced Financial Visibility: Clear view of financial health, cash flow, and expense breakdown.
* Increased Data Literacy: More accessible and understandable data visualizations.
* Scalable Analytics: Template library supporting businesses of various sizes and industries.
* Competitive Edge: Advanced analytics capabilities giving QBO customers an advantage in their markets.

## Risks / Limitations / Challenges
* Setting up and configuring PostgreSQL locally.
* Trying to understand how the QuickBooks & Unified API works and interpreting its documentation.
* Understanding and aligning new projects with the existing GitHub codebase.
* Ensuring version compatibility and developing comprehensive test suites.
* Documenting the process and implementing version control for schemas and code.
