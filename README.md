# Group 4 (UniTrade – Settlement and Reporting)
## Team Members
Sai Rahul Dasari - Product Manager/ Business Analyst  
Gurukiran Reddy Kasireddy - Microservices Developer  
Sindhu Maddineni - UI/UX Designer  
Daniel Sarzynski - Data Architect  
Xinghan Yin - Quality and DevOps  
 
## Product Vision 
### Far Vision for the product
The Settlement and Reporting module is designed to simplify the process of buying and settling trades on the UniTrade platform. Our long-term vision is to create an automated, transparent, and secure system that manages all transactions accurately using microservices. The key goals of our module are:
* Once a buyer confirms a purchase, we lock in the price and update the backend system so it becomes part of the platform’s historical data.
* Make sure every trade is settled quickly and without errors, by using a series of specialized microservices.
* Generate detailed reports that help traders keep track of their transactions and understand potential risks.
* Address major trade issues through a strong risk management system, including:
 ** Insufficient Funds: Ensure trades only go through if buyers have enough money by checking their balance at important stages.
 * Counterparty Risk: Reduce the chance of a trade falling apart by analyzing past user behavior to ensure both parties meet their obligations.
 * Settlement Failures: Prevent problems with trade settlement, making sure goods and payments are exchanged on time and correctly.
This vision supports the broader goals of the UniTrade platform by making post-trade processes as smooth, reliable, and secure as possible—just like the trade execution itself.

### Near vision for the first iteration
In the first iteration, we’ll focus on building the basic components of the Settlement and Reporting module. Here's what we plan to accomplish:
Design specific use cases for settlement and reporting functionalities, and create test cases to make sure everything works as expected.
Set up database tables to organize and categorize data effectively.
Implement basic trade settlement processes to make sure goods are delivered and payments are made smoothly.
Create initial reports that show essential info like transaction histories and account balances.
Add basic margin and balance checks to prevent trades from failing due to insufficient funds.
Build a simple, user-friendly interface where users can view their post-trade reports and balances.
This iteration will serve as the foundation for future improvements, ensuring that the core settlement and reporting functions are working well from the start. 


## Stakeholders
For the Settlement and Reporting module, we’ve identified three main groups of people who will benefit from our work:
Traders (Buyers and Sellers): These are the people using the platform to buy and sell products. They need the settlement system to work efficiently, with accurate reports on their trades, prices, and account balances. Quick access to these reports helps them track their performance and make sure they’re following all the rules.
Platform Administrators: These are the people who manage and monitor the platform. They need a clear and transparent way to track every trade and settlement to ensure everything is running smoothly. Real-time reports and audit logs help them keep an eye on the platform’s overall health and manage risks.
Risk Management Officers: These are the people responsible for making sure the platform doesn’t lose money due to trade failures. They need the system to automatically check margins and balances at key moments to ensure traders have enough funds, reducing the chances of a trade falling through.


