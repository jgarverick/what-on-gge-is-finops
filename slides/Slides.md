---
marp: true
theme: midnight
transition: fade
style: |
  .columns {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 1rem;
  }
  .columns3 {
    display: grid;
    grid-template-columns: repeat(3, minmax(0, 1fr));
    gap: 1rem;
  } 
  img[alt~="center"] {
    display: block;
    margin: 0 auto;
  }
  
  @import 'https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.3.0/css/all.min.css'
---
<!-- _class: "title-slide" -->
# What on God's Green Earth is FinOps?
![bg right](https://learn.microsoft.com/en-us/azure/cost-management-billing/costs/media/tutorial-acm-create-budgets/cost-analysis.png#lightbox)

---

## What is FinOps, really?

According to the [FinOps Foundation](https://www.finops.org/introduction/what-is-finops/):

>"FinOps is an evolving cloud financial management discipline and cultural practice that enables organizations to get maximum business value by helping engineering, finance, technology and business teams to collaborate on data-driven spending decisions."


---

## Customer Profiles

Customers tend to look into FinOps as a practice because:
- They want to be fiscally responsible
  - Avoidance of duplicative costs
  - Prior experiences with runaway spend
- They don't understand how consumption is billed
- They want to pay for as little as possible
- They want teams to have skin in the game

---

## Common Use Cases

- Cost awareness
- Cost containment
- Accounting gymnastics (chargebacks)

---

## Enablement

- Proactive vs Reactive
  - Proactive: Budgets and Alerts
  - Proactive: Utilization Profiles
  - Reactive: [Service Disabling via Automation](https://samcogan.com/enforce-budgets-with-cost-management-and-logic-apps/)
  - Reactive: [Reporting on the Consumption APIs](https://learn.microsoft.com/en-us/azure/cost-management-billing/costs/analyze-cost-data-azure-cost-management-power-bi-template-app)
- Infrastructure as Code
  - ARM
  - [Bicep](https://learn.microsoft.com/en-us/azure/cost-management-billing/costs/quick-create-budget-bicep?tabs=CLI)
  - [Terraform](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/resources/consumption_budget_resource_group)

---

## Q&A Matinee

