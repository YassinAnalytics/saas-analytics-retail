# Saas Analytics Retail
Custom analytics dashboard for omnichannel retailers (Power BI alternative)



## Context
I was contacted by a the CMO of a company that runs both an e-commerce website and physical retail stores. They were already using Power BI but only in a limited way and most employees don’t have the time or knowledge to use It effectively. The leadership team needs better visibility, insights, understand and leverage their data.


I designed a SaaS solution concept with a series of dashboards tailored to their needs, including:
- A Global Dashboard: with key business metrics such as total sales average basket, conversion rate, active customers, sales evolution, location sales.
- A Campaign Dashboard: showing campaign performance over time, comparisons between campaigns, active customers, conversion rate, and an overview of all the previous campaigns of the year.
- A Sales Dashboard: focusing on sales trends by product, which product, how many issues reported, number of returns, the stock states.
- A customization part, with a dark mode, colored AI proposed for the reporting, and possibility to apply all AI recommendations at once.
- An export section, where can be chosen how the export shall be done (PDF, email), which section include and possibility to write a message.


The MVP (Minimum Viable Product) includes a desktop version only, with future developments planned:
- A mobile-friendly version.
- A PDF export feature with customizable comments.
- AI-powered insights to suggest:
 - Smart restocking decisions.
 - Alerts on underperforming products.
 - Personalized recommendations for future campaigns.
 - A customization part.






## Saas Schema
 ![image](https://github.com/user-attachments/assets/6b9932b0-f641-4c57-989d-c984943ab49b)


The stars represent the MVP features.


## Roadmap (Phased Approach)
**Phase 1 – MVP**

Goal :  to Deliver a working desktop prototype with core dashboards that the teams can use right away as the needs is urgent.

- Define key KPIs with stakeholders.
- Collect and clean the necessary data.
- Build Power BI dashboards: Global, Campaigns, Sales.
- Deploy a basic desktop version (internal use only).
- Get initial feedback from users.
- Which and how data to connect.

**Phase 2 – Iteration & Mobile Version**

Goal: Improve based on feedback and add mobile version.

- Improve UX and visuals of dashboards and dark mode.
- Optimize performance.
- Build mobile-compatible views (responsive app).


**Phase 3 – AI Integration & Automation**

Goal: Add intelligent recommendations and automation.

- Develop rules or ML-based suggestions (e.g. stock alerts, product focus).
- Integrate performance alerts (low stock).

**Phase 4 – SaaS Productization (Optional – future vision)**

Goal: Turn the internal tool into a scalable SaaS offer.

- Design multi-tenant infrastructure.
- Add user authentication, roles & permissions.
- Create onboarding flows and dashboard templates.
- Automate export and reporting.
- Enable real-time or scheduled refresh.
- Launch a paid version or offer it as a service.

With the go-live of the MVP, the analysis time is expected to be reduced by 35%, then once the AI tools released, it’s expected to be reduced by 50%. And a 100% rate adoption by the employees.

The roadmap is structured in 4 phases, from MVP definition to SaaS productization. It includes desktop, mobile and AI developments:

![image](https://github.com/user-attachments/assets/8bba2441-bb60-45fd-a3d2-97df670ab169)


 

This roadmap outlines the evolution of the SaaS solution from MVP definition to productization. It is structured in 4 phases across 3 main components: Desktop, Mobile, and AI.
Each color corresponds to a specific team involved, as shown in the legend.
- Phase 1 (Q1): MVP scope definition, core dashboard development, QA, and first go-live (desktop).
- Phase 2 (Q2): Mobile development, UI/UX improvements (including dark mode), and mobile release.
- Phase 3 (Q3): AI module development, integration of rules and alerts, and AI QA/go-live.
- Phase 4 (Q4): SaaS productization with infrastructure setup and multi-client readiness.
Each milestone was prioritized based on urgency, business value, and technical feasibility — ensuring fast time-to-value, scalability, and strong user adoption from the very first phase.





## Design of each page
![image](https://github.com/user-attachments/assets/9989a98d-4cd7-4c7b-affe-41662abbf4fe)



The first page shows an overview, in few seconds, all the main data are available. A panel of colors is also used to get the attention about some metrics that has been decided at are used as alert point; In this page, we have an overview of the global performance of the company, following the dates applied.

 
 ![image](https://github.com/user-attachments/assets/2b6629ee-4428-40f2-a12c-bac9eaab8afd)

This page is focused on the campaigns, where it’s easy to see the global performance of the campaigns. Knowing that the tags of the campaigns have been set up previously, by clicking on one campaign, the metrics will be updated automatically. 

 ![image](https://github.com/user-attachments/assets/eaeb5d95-3513-4ec7-8890-c09f531e146e)

This part is about the products and is meant for the product overview for the logistics and supply chains team. From it they can monitor all the deliveries, stock filling by product, while getting updated information from the shops and warehouse thanks for the stock management system of the company.

 ![image](https://github.com/user-attachments/assets/a57999a2-1ec6-44af-b8d1-a7cd344f4b30)

This part is not in the MVP but will be used to configure the app and the dashboard, following the color panel of the company and the possibility to let the AI recommend and update everything following the best case.

 ![image](https://github.com/user-attachments/assets/96f93f1e-dd7a-408d-b610-1f1b6c80a7b4)

This part will allow the export into a PDF report or send by email. The user can select which part of the data wanted for the export. A message can be written before the report is generated.

 ![image](https://github.com/user-attachments/assets/4c2de865-bbfd-45aa-ba3f-333f3c884923)

The dark mode version has exactly the same features as the light version.
 
![image](https://github.com/user-attachments/assets/e2a2f6b7-1da9-4fbc-88bb-aa5739171768)


The mobile/responsive version will arrive at a later stage as following the company request, it will be used for quick check of data, but most of the monitoring will be done on the desktop version. Nonetheless, the app contains the exact same features and view as the desktop version. The app would also contain a dark mode version.


