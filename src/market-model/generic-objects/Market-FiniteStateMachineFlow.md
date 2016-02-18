#The market flow

In a market, a client came to a distant sale endpoint and request a product or service.
The sale endpoint deliver to the client the product and report to central authority (self authority) if any the transaction.
If the product is not available, it send a request
on messaging channel provided by central coordination server in order to find if the product is available 
The server permit multiple function of finding the product 
In this scenario (1)
The operator will receive   a list of providers registered for the goods or service
the client is looking for
After the operator select one or more possible providers , the server forward the request  to IManufacturer server where it is processed by an operator.
an operator that confirm/drop the request and begin a 2 way negociation with the sale point op. If the sale drop the negociation all involved party will be 
notified.

The second scenario is similar to an auction system where the server send initial request to all registered manufacturers. Their operators begin an auction like 
system and at the end the salepoint receive a notification of the best offer

The third scenario is when the request from the salepoint is processed by a search system based on published offers without no intervention from 
the manufacturer side. 

For all scenarios, a message that travel between actors have multiple time limits: for droping, for response confirmation and other operations,
ensuring all the operations are ok. Also, the rate of response and other informations are hosted into a "profile" for both sale endpoint and 
manufacturer. Also the system is discount integration ready - so the client can benefit from sale point discount system or manufacturer/warehouse discount system. 
No personal information is exchanged, the real client is a hash in all data exchange involved. The hash algorithm ensure  client identification, invoice identification,
payment and discount rights.

The next step is the payment step. The sale point assemble an invoice request to the manufacturer and after final confirmation, allow the client 
to make a payment. The client is issued a voucher-like information for future reference. The payment information is sent to the selected payment 
provider and the transaction is confirmed to the manufacturer/wharehouse 

The goods are sent from the warehouse to the delivery channel that can request more information from sale point about for example delivery address
if no one was provided already.

All actors have the opportunity to publish in the system reports about transactions and other business tools.

This directory provide common object representation for above flow.

Please visit http://www.ambigram.ro and  http://www.e-reducere.ro for more information about our projects

