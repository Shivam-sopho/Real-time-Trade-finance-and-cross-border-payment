# Trade Finance and Cross Border Payments in Real Time using Hyperledger Fabric

## Trade Finance 
The function of trade finance is to introduce a third-party to transactions to remove the payment risk and the supply risk. Trade finance provides the exporter with receivables or payment according to the agreement while the importer might be extended credit to fulfill the trade order.

## Issues with Trade Finance
Trade financing, where financial institutions provide credit facilities in order to guarantee exchange of goods, is a centuries old industry that hasn’t seen much change with the growth of global trade flows. There are flowing pain-points & inefficienes in the current system - 
1. Manual contract creation - The import bank manually reviews the financial agreement provided by the importer and sends financials to the correspondent bank
2. Invoice factoring - Exporters use invoices to achieve short-term financing from multiple banks, adding additional risk in the event the delivery of goods fails
3. Delayed timeline - The shipment of goods is delayed due to multiple checks by intermediaries and numerous communication points
4. Manual AML review -The export bank must manually conduct AML checks using the financials provided by the import bank
5. Multiple versions of the truth: As financials are sent from one entity to another, significant version control challenges exist as changes are made
6. Duplicative bills of lading: Bills of lading are financed multiple times due to the inability of banks to verify their authenticity
7. Multiple platforms: Since each party across countries operates on different platforms, miscommunication is common and the propensity for fraud is high

## Benefits while using blockchain for Trade Finance 
![image](https://user-images.githubusercontent.com/21002170/134018007-887f8c64-9771-4b7a-a80c-fcc18b1c0649.png)


## Current Flow for Trade Finance 

![image](https://user-images.githubusercontent.com/21002170/134015842-12a29e9f-409c-485d-a040-4e4a3e8841ba.png)

![image](https://user-images.githubusercontent.com/21002170/134015415-d8bcc3b7-68c5-4c0c-98a6-7aaf84dd3c60.png)

## Cross Border Payments
Remittance is a fund-transfer transaction wherein are moved from one account to another account within the same or different financial institution. In a cross-border payment, SWIFT handles only the movement of messages along with payment chain. The correspondent banks do the actual debits and credits across accounts based on the message and helps pass on the vlaue to the final beneficiary.

## Issues/Drawbacks with Cross Border Payment Process
1. Since no two banks can agree on the transaction based on their own ledger, SWIFT came into being to guarantee and confirm message transmission. Central banks operated as settlement agents to guarantee payments.
2. SWIFT charges the bank for processing orders irrespective of whether the bank is at the both the receiving and sending end of instruction
3. A single cross-border payment has to traverse through certain correspondent banks which are involved in activited like receiving, collating, and netting payment meesages before retransmitting confirmations. This increases the time to settle. 

## Benefits of using Blockchain 
1. It leads to exclusion of any middlemen, central agencies, or correspondents from payment processing. 
2. Reduced cost with minimal charges along with the payment chain.
3. Reduced turnaround time for settlement as there is no need for central agencies and movement of messages. 

## Current Flow 
![image](https://user-images.githubusercontent.com/21002170/134014752-d1f847b4-2ba7-475a-8348-682bcd7adcc7.png)


# Idea for Solving above issues with Hyperledger based Blockchain System
## Trade Finanance Using Blockchain
1. Digitize the entire trade finance lifecycle with increased security and efficiency.
2. Digitized and authenticated documentation (i.e. letters of credit and bill of lading) and KYC/AML data with real-time verification of financial documents
3. Creation of more efficient financing structures through shared secure networks and digitized processes
4. Our system will allow the parties required to track the transactions with ease. Using smart contracts to automate workflows and clearing calculations reducing processing time and benefit the banks by reducing errors resulting from human mistakes.
5. Out system will allow creation of a consistent financing vehicle for the entire trade lifecycle, eliminating the legacy practice of negotiating independent finance vehicles for each stage of the trade

## Flow using Blockchain


## Cross Border Payments using Blockchain
Blockchain solves these challenges by streamlining the process and storing
every transaction in a secure distributed ledger.
1. As soon as a transaction is recorded, the receiving party has access to the payment – no middlemen, no delays, no unnecessary fees.
2. And once a payment is entered, it can’t be reversed or changed in the ledger, fostering greater overall accountability and security
3. Due to decentralized network Company A in the U.S. and Company B in India see the exact same information in one place, instead of in five databases in different cities
4. Our payment system on the blockchain will also facilitates banks to get rid of all intermediaries in the payment processing system to lower the costs to process payments between banks and clients.
5. Here Also like Trade financing our app, will Digitized KYC/AML data and transaction history, reducing risks of fraud and enabling real-time authentication
 Some financial institutions have outdated, and thus inefficient databases and reporting systems.
6. Distributed ledger technology is set to revolutionize the way financial
data is recorded and exchanged within the bank as well as between
banks or between banks and corporates.
7. The idea of a semi-manual data reconciliation should become obsolete when blockchain becomes interwoven into banks’ daily operations. This is because blockchains act as a database that is secure and immutable.
8. Will every completed transaction we will store the data on the immutable decentralized network of blockchain will keep the data safe.
9. All large amount of record keeping transaction and operations can be recorded using blockchain distributed ledgers that are unalterable and impede fraud

## Challenges tackled
1. By cutting out many of the traditional middlemen, the laborious and costly process of cross border payments is simplified, thus significantly speeding up the cross-border  payment process and that at a cost much less than with the traditional banking systems.
2. Blockchain-based trade finance can streamline the entire trading processes by getting rid of this time-consuming paperwork and bureaucracy. It eliminates the need for several copies of the same document and canintegrate all necessary information in one digital document, which is updated in real time and can be accessed by all network members.
3. Additionally, blockchains native ability to create and transfer digital assets enhances various existing commodities trading processes outlined above.
4. The real-time data and transactions enabled by smart contracts has the potential to reduce delays and automate manual processes. The inefficiencies throughout the commodities trade industry result in a loss of income and opportunities for businesses.
## Individual Flow chart for Cross Border Payments
![image](https://user-images.githubusercontent.com/21002170/134014624-5bd9ee64-9ec5-4117-80e4-7d9201f7cf86.png)


## End-end Flow Pipeline for whole project
![image](https://user-images.githubusercontent.com/21002170/134014325-6c384d36-3b66-478f-9260-c1ea9f249d43.png)

