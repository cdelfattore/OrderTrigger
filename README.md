# OrderTrigger
Sample Salesforce order trigger. The requirements for the Apex trigger were as followed.

ABC Manufacturing using Accounts, Opportunities, Quotes, Contracts and Orders to manage their sales and delivery operations. They want to provide Force.com users with insight into Order totals for each Account so they want a custom field to be created on the Account object to house “Order Totals this Year” as well as another custom field to house “Order Totals Last Year”.

Sometimes, Orders can be created accidentally by users and require a system admin to delete those records but being as there are two system admins within this company, sometimes an Order is deleted by accident and needs to be recovered from the Recycle Bin. 

For this objective, you’ll be required to write a trigger to handle this requirement and make sure that those totals are accurate and can accommodate those user issues
