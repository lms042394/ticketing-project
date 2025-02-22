# Ticketing System Overview

In this walkthrough, we will explore handling problem tickets using osTicket, an open source solution similar to ServiceNow and Jira.

## Ticket examples

### User's perspective - mobile & online banking offline for accounting department
**Video version:** <https://youtu.be/2QPpb0GyFmM>  
![Screenshot](https://i.imgur.com/46ztifW.jpeg)  

The end user and employee's supervisor asks her team to confirm if everyone's having the same issue, then submits the ticket on the Web-based portal. She chooses only a first-level case classification (Report a Problem).

### IT's perspective
**Video version:** <https://youtu.be/AmiS9gcEEBY>  
![Screenshot](https://i.imgur.com/lHOH4gZ.jpeg)  

A help desk analyst notices the open ticket had entered the Support team's bucket, and begins by setting its properties to the following:

* **Priority:** High (entire team is affected and it's the accounting department during tax season)
* **Assigned to:** Online Banking (a team composed of members from both the SysAdmin and Support departments)
* **SLA Plan:** Sev-A (highest SLA, 1 hour required response time 24/7)
* **Help Topic:** Report a Problem / Business Critical 

A different analyst who's available responds to the creator of the ticket to acknowledge it. It's marked as overdue because the ticket was sent in at 6:10 PM, but only was replied to by 8:20 PM, when it should have gotten a reply before 7:10 PM.

Before the ticket is triaged, the analyst checks the trending issues, and notices that it's been reported that this issue began after a backend software update.

The analyst then begins triage by rolling back the update (downgrading) for the accounting department, then contacts the supervisor back to see if the issue persists.

The ticket creator then confirms that her team can now access the mobile and online banking system again. It's closed as Resolved because this is an unexpected issue.

### User's perspective - two members of accounting department requesting Adobe Reader update
**Video version:** <https://youtu.be/F4MyN0E4rno>  
![Screenshot](https://i.imgur.com/xNGyk5V.jpeg)  

This time, the employee submits the ticket for himself and his only other colleague who is experiencing the issue, after asking his supervisor how she did it previously.

### IT's perspective
**Video version:** <https://youtu.be/NZSe3-fw1mo>  
![Screenshot](https://i.imgur.com/u5FKge7.jpeg)  

An IT support analyst responds to the creator of the ticket to acknowledge it, and in real time this time, with the following properties:

* **Priority:** Normal
* **Assigned to:** (Left blank because the analyst worked on this ticket right away and it didn't need collaboration, but he should have assigned it to himself so other analysts would be aware and not start working on it unnecessarily)
* **SLA Plan:** Sev-B (4 hours required response time 24/7)
* **Help Topic:** Report a Problem / Personal Computer Issues

The analyst sees that an update to Adobe Reader hasn't been pushed to the two users' workstations yet, and it's better that they install it first - instead of triaging by restarting the computer first, because the update requires that the computer be restarted anyway and no issues have been reported because of it.

The analyst then follows up with the user, who confirms that the issue is now resolved for both of them. It's closed as Resolved because this is an unexpected issue.

### User's perspective - C-suite officer's laptop not turning on
**Video version:** <https://youtu.be/XyKYgYRzxZc>  
![Screenshot](https://i.imgur.com/3zOll9m.jpeg)  

The employees' supervisor passes by the company CFO (chief financial officer) at his desk, who mentions the issue to her during their short conversation, so she submits a ticket on the portal on his behalf.

### IT's perspective
**Video version:** <https://youtu.be/otYxxAuAenU>  
![Screenshot](https://i.imgur.com/JdM5SzM.jpeg)  

A service desk analyst responds to the creator of the ticket to acknowledge it in a timely manner, with the following properties:

* **Priority:** Normal
* **Assigned to:** (May or may not be left blank depending on company policy)
* **SLA Plan:** Sev-B (4 hours required response time 24/7)
* **Help Topic:** Report a Problem / Personal Computer Issues (the creator of the ticket selects the second-level classification as well this time)

The analyst acknowledges the ticket and notifies the creator that he will seek out the CFO to investigate the issue personally.

After a short chat with the CFO when he was available, the analyst then tests charging the laptop with another power adapter first, a less invasive solution than trying to use keyboard-based commands to see if the laptop will turn back on that way.

The analyst then updates the ticket with his diagnosis and resolution even if he solved the problem in person, for performance- and metric-tracking purposes. The ticket is closed as Closed because functioning equipment is what was able to fix it.
