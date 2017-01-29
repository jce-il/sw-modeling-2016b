## Actors Table

| Actor/Stakeholder | Target |
|-------|--------|
| Registered Customer | wants to buy a DVD |
|       | wants to pay a bill |
|       | wants to request tech. support |
| New Customer | wants to register |
|       | wants to request tech. support |
| Logistics Manager | needs to enable order shipment |
| Parcel Service | needs to deliver order |
| Authentificaton service | needs to register new users |
|       | needs to authentificate service users |
| Support Team | needs to provide tech. support for service users |
| Developers Team | needs to fix bugs / develop new enhancements |
| On-line credit card service | needs to provide safe on-line payments |

## Use-cases Diagram

![Use case diagram](https://github.com/katyadenef/sw-modeling-2016b/blob/master/UseCaseDiag.PNG)

## Detailed Use-case

| Subject | Description |
| -------|--------|
| Use-case name | Technical support Request |
| Main actor | web customer |
| Goal | the customer wants to get technical help since he's not able to perform a specific action |
| Scope | web-service for products purchase |
| Level | web customer |
| Actors/Stakeholders | <ul><li>customer - wants to receive help</li><li>support team - want to provide high level support to customers</li><li>service owners - want the customer to be satisfied with the support and continue using their service</li></ul> |
| Trigger | customer clicks the "Get Help" button |
| Pre-requirement | customer has trouble fulfilling a mission |
| Successful Ending Condition | customer succeeds in his mission; the support team closes the ticket |
| Failure Condition | technical support cannot provide a solution, e.g., a bug is found |
| Main successful scenario | <ol><li>customer clicks the "Get Help" button</li><li>the customer fills out the form</li><li>a ticket is opened in the system</li><li>the systems connects the customer to chat with a support agent</li><li>the customer explains his issue</li><li>the support agent resolves the issue</li><li>the customer manages to do his task and closes the chat with the agent</li><li>the support agent closes the ticket</li></ol> |
| More (errors) | <ul><li>support agent is unavailable<ul><li>the customer is asked to wait on the line</li><li>the customer gives up and looks for another way to do what he needed to do</li></ul></li><li>the support team cannot resolve the issue, coz it's a bug and needs to be fixed by developers</li></ul> |
| Aternative Scenario | the customer find a phone number to call for thechnical support |
</br>
</br>
&copy; Katya Denef, Ran Itzhaky, Itzik Rabinovich
