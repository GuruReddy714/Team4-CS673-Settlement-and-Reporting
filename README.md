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
  * Insufficient Funds: Ensure trades only go through if buyers have enough money by checking their balance at important stages.
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

## User Persona for our Stakeholder
Emma Chen is a Platform Administrator, she is responsible for overseeing the UniTrade platform’s backend operations, focusing on ensuring smooth and accurate settlements. Her role involves monitoring trade settlements, resolving any discrepancies, and managing the platform’s financial health. Emma needs access to real-time data, audit trails, and reporting tools that allow her to identify potential issues quickly and maintain compliance across the platform. She prefers tools that give her transparency and control over all trade-related activities.

Goals:
* Ensure all trades settle on time with no discrepancies.
* Monitor real-time reports and audit logs to ensure platform health.
* Quickly identify and resolve any settlement or balance issues before they escalate.

Pain Points:
* Inconsistent or delayed reporting can make it harder to address issues in real-time.
* Lack of transparency in the settlement process, leading to potential risks.
* Difficulty accessing detailed audit trails during high-volume trading periods.

## 10 Product Backlog items
### High Priority
* As a buyer, I want to register an account so that I can start using the platform for shopping.
* As a seller, I want to create product listings so that I can start selling items on the platform.
* As a buyer, I want to search for products so that I can find what I want to purchase.
* As a buyer, I want to view product details, including images, descriptions, and prices, so that I can make informed purchasing decisions.
* As a buyer, I want to add items to a shopping cart so that I can purchase multiple items at once.
* As a buyer, I want to complete the payment process securely so that I can purchase the selected items.
* As a seller, I want to view and manage my orders so that I can process and ship them in a timely manner.

### Medium Priority
* As a user, I want to view and edit my profile so that I can update my information.
* As a buyer, I want to rate and review sellers and products so that other users can learn from my shopping experience.
* As a seller, I want to respond to buyer reviews so that I can provide additional context or address issues.
* As a buyer, I want to set up product alerts so that I'm notified when items I'm interested in are discounted or back in stock.
* As a user, I want to communicate with other users through an in-site messaging system so that I can ask questions about products.

### Lower Priority
* As a buyer, I want to create and manage wish lists so that I can save items I'm interested in but not ready to purchase.
* As a seller, I want to view sales analytics and reports so that I can understand my sales performance.
* As a user, I want to set language and currency preferences so that I can use the site in my preferred language and currency.
* As a buyer, I want to participate in auctions so that I can bid on unique or rare items.
* As a user, I want to access the platform through a mobile app so that I can shop or manage my listings on the go.
* As a seller, I want to set up bulk discounts or promotions so that I can attract more buyers and increase sales.

### Technical Tasks
* Set up and configure database schema
* Implement user authentication and authorization system
* Set up payment gateway integration
* Optimize search functionality performance
* Implement image upload and storage system

### Bug Fixes
* Fix mobile layout issues on product pages
* Resolve slow loading of payment page on certain browsers
* Fix bug preventing user reviews from being submitted

### Improvements
Optimize website loading speed
Improve mobile UI responsiveness
Enhance website accessibility for screen readers
5. Spikes
Research and evaluate different recommendation system algorithms
Explore feasibility of real-time chat functionality
Investigate use of blockchain technology for secure payments
6. Non-functional Requirements
Ensure the website can handle at least 1000 concurrent requests per second
Implement 99.9% system uptime
Ensure all pages load in under 3 seconds
7. Documentation and Training
Create user manual
Write API documentation
Prepare training materials for customer service team
8. Legal and Compliance
Ensure website complies with GDPR data protection requirements
Update terms of service and privacy policy
Implement necessary security measures to comply with PCI DSS standards




