Exploring Healthcare Costs
-----------------------
#### US Healthcare Costs
The US spends $3 trillion per year on healthcare. It spends more per capita on healthcare than any other country. The US spends about 18% of its GDP on healthcare which is 2 to 3 times more than other countries.

Various factors are attributed to this:
* high inpatient/outpatient treatment costs
* high administrative costs
* defensive medicine causing unnecessary treatments
* hospital consolidation causing monopolies
* medical billing codes becoming a business in itself to maximize revenue
* no negotiation mechanism for price control for private insurance
* providers can charge what the market will bear

The Medicare program run by the government does have a price control mechanism. It has a standard for payments based on the DRG (Diagnosis-Related Group) system and gets lowest prices. In contrast for the rest of the insurance market, providers can more or less charge whatever they can.

In this project, I have analyzed summary **Medicare payment data** for the **top 100 DRGs** from 2011. The data is available [here](https://data.cms.gov/Medicare-Inpatient/Inpatient-Prospective-Payment-System-IPPS-Provider/97k6-zzx3) at the CMS website.

#### What is CMS?
The Centers for Medicare & Medicaid Services (CMS) is a federal agency within the United States Department of Health and Human Services (HHS) that administers the **Medicare program** and works in partnership with state governments to administer Medicaid, the State Children's Health Insurance Program (SCHIP), and health insurance portability standards.

#### What is a DRG?
A Diagnosis-Related Group (DRG) is a statistical system of classifying any hospital hospital/inpatient stay into groups in order to facilitate payment of services. The DRG classification system divides possible diagnoses into more than 20 major body systems and subdivides them into almost 500 groups for the purpose of Medicare reimbursement. Each DRG is expected to have similar hospital resource use and hence comparable charges/payments.

#### Severity Tiers in DRGs
DRGs can have following Severity Tiers based on increasing complexity and cost of care and higher payments:
* DRG without CC or MCC
* DRG with CC (complication or comorbidity)
* DRG with MCC (major complication or comorbidity)
For example, Heart Failure & Shock has the following three DRGs:
* 293 - HEART FAILURE & SHOCK W/O CC/MCC
* 292 - HEART FAILURE & SHOCK W CC
* 291 - HEART FAILURE & SHOCK W MCC

#### About The Data
**Inpatient Prospective Payment System (IPPS) Provider Summary for the Top 100 Diagnosis-Related Groups (DRG) - FY2011**
The data includes hospital-specific charges for the more than **3,000 U.S. hospitals** that receive Medicare IPPS payments for the top 100 most frequently billed discharges, paid under Medicare based on a rate per discharge using the Medicare Severity Diagnosis Related Group (MS-DRG) for Fiscal Year (FY) 2011. These DRGs represent more than **7 million discharges** or 60 percent of total Medicare IPPS discharges.

#### My Objective
As part of this project I will be exploring the data and creating visualizations to depict:
* variation in charges by providers for DRGs across states
* variation in Medicare payments to providers for DRGs across states
* variation in the overcharge (difference between charges and payments) for DRGs across states

#### My Approach

#### My Observations
