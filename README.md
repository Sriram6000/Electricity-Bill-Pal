# Electricity-Bill-Pal
Electricity Bill Pal automates electricity bill processing in multi-apartment buildings using AI. It extracts bill details, maps them to residents, and delivers digital copies via email, reducing manual errors and delays. 
Electricity Bill Pal – Automating Utility Bill Distribution

**Background**

In my multi-storey apartment complex with 100+ residents, electricity bills are manually distributed by the security guard. Every month, electricity board officials generate paper bills and leave them near the meter box. The security guard then:

-  Matches each bill’s USC number with his ledger, mapping it to a resident's door number.
-  Handwrites the door number on each bill.
-  Delivers the bills door-to-door.

This **manual process** leads to multiple inefficiencies:

-  Errors in bill distribution (wrong bill to the wrong resident).
-  Missed payments due to delays in handing over bills.
-  Security guard’s productivity loss, spending half a day on this task.
-  Disconnections & disputes, as residents fight over missed due dates.

**The Solution: Automation with Power Platform**

To eliminate manual errors and inefficiencies, I developed a **Proof of Concept (POC)** using **Power Platform**:

1. **Canvas App** – Security guard takes a photo of each bill. The image is saved in Dataverse.
2. **Power Automate** – Extracts key details (USC No., bill amount, due date, etc.) using a Document AI model and updates the Dataverse table.
3. **Email Notifications** – Residents receive an automated email with:
  -  Bill details (USC No., amount, due date, disconnection date).
  -  A soft copy of their bill attached.

**Future Enhancements**

-  Automated Due Date Reminders via email/SMS/push notifications.
-  Power BI Dashboard to track electricity usage trends.
-  Unified Resident Portal for bill disputes & issue resolution.
  
**Impact**

This solution significantly reduces manual effort, minimizes errors, and ensures residents receive bills on time, preventing disconnections. It also allows the security guard to focus on actual security duties rather than administrative tasks.

I built this project as part of Microsoft's Powerful Hack in just one day! There’s still room for improvements, but this is a great example of **how automation can make everyday processes easier for the common man**.

**Would love to hear your thoughts! How else can this be improved?**
