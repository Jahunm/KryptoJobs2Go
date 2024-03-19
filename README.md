# ***KryptoJobs2Go*** 
 
![crypto wallet](/Images/19-4-challenge-image.png)

*Module 19 Challenge - Building a Crypto wallet with Ganache, Web3.py*

# Table of Contents
1. [Introduction](#introduction)
2. [Overview of KryptoJobs2Go](#overview-of-kryptojobs2go)
3. [Key Features](#key-features)
4. [Overview of the KryptoJobs2Go Web App](#overview-of-the-kryptojobs2go-web-app)
5. [Benefits](#benefits)
6. [Technologies Used](#technologies-used)
7. [Conclusion](#conclusion)
8. [Contact Us](#contact-us)

## **Revolutionizing Fintech Hiring with KryptoJobs2Go** 
---
### Introduction
At KryptoJobs2Go, we are dedicated to revolutionizing the way fintech professionals are hired and paid. Our platform offers a seamless solution for finding, hiring, and paying fintech experts using cryptocurrency. In this report, we will explore the innovative features of KryptoJobs2Go and explain how it benefits both customers and fintech professionals.

### Overview of KryptoJobs2Go
KryptoJobs2Go is a cutting-edge platform designed to simplify the process of hiring and paying fintech professionals. Our platform leverages the power of the Ethereum blockchain network to enable instant and secure payments using cryptocurrency. By integrating blockchain technology, we ensure transparency, security, and efficiency in the hiring and payment process.

### Key Features
- Streamlined Hiring Process: With KryptoJobs2Go, customers can easily browse through a curated list of fintech professionals and select the candidate that best fits their needs. Our user-friendly interface makes it simple to review candidate profiles and make informed hiring decisions.

- Instant Payments: Gone are the days of waiting for payment processing. KryptoJobs2Go enables instant payments using cryptocurrency, ensuring that fintech professionals receive their compensation promptly for their services.

- Blockchain Security: The Ethereum blockchain network provides a secure and immutable ledger for recording transactions. By leveraging blockchain technology, KryptoJobs2Go ensures transparency and eliminates the risk of fraud or tampering.

### Overview of the KryptoJobs2Go Web App
1. The homepage of our webapp shows a list of all the potential canidates you can choose from. 
![Home Page](/Images/webappsample.png)
Each professional includes
- Picture
- Ethereum Account Address
- Overall rating left by user from our website
- Hourly rate in Ether  
---
2. Here is a closer view at how you can choose your professional and the amount of time you would like to book.
![Selection option](/Images/webappselector.png)
Listed from top to bottom 
- Account holders Ethereum address (Yours)
- Account holders current ETH balance
- drop down bar to select a Pro
- Entry box allowing user to determine length of time needed
- Candidate ETH address and wage (calculated in eth) will automatically populate 
- Send Transaction button is there if you like what you see and you want to book the time slot with the pro of your choice
---
3. Book your Pro
![Time Booked](/Images/validated_hash.png)
Once you press the send button, time is book with the pro and time. Payment is sent immediately and verified on the blockchain, by way of the transaction hash.
In my example I choose Jo for 7 hours and the wage in Ether at her rate * 7 hours is 1.33 ETH
---
4. Here we can verify the wallet address is the same as the users account wallet address. Matching the website. 
![Ganache wallets](/Images/ganache_step1.png)
address and bnalance match the ones listed on the streamlit web app
---
5. Screenshot of the transaction 
![Verifing Transaction](/Images/ganache_trans_verified.png)
Here we can see that Jo, wallet address 0x8fD00f170FDf3772C5ebdCD90bF257316c69BA45, was sent 1.33 ETH 

### Benefits
- Efficiency: KryptoJobs2Go streamlines the hiring and payment process, saving time and resources for both customers and fintech professionals.
- Transparency: Blockchain technology ensures transparency in transactions, providing a clear record of payments and ensuring trust between parties.
- Global Accessibility: By accepting cryptocurrency payments, KryptoJobs2Go expands access to fintech talent and enables cross-border transactions without the need for traditional banking systems.

### Technologies Used
 - Python: Python is the primary programming language used for developing KryptoJobs2Go. It offers versatility, ease of use, and a wide range of libraries for blockchain integration and web development.
 - Ganache: Ganache is a local Ethereum blockchain emulator used for testing and development purposes. It allows us to simulate blockchain transactions in a controlled environment.
 - Web3: Web3 is a JavaScript library used for interacting with Ethereum smart contracts and blockchain networks. It enables communication between our web application and the Ethereum blockchain.
 - Streamlit: Streamlit is a Python library used for building interactive web applications. It allows us to create a user-friendly interface for browsing candidates, making payments, and managing transactions on KryptoJobs2Go.

### Conclusion
KryptoJobs2Go is poised to revolutionize the fintech hiring industry by offering a seamless platform for finding, hiring, and paying fintech professionals using cryptocurrency. By leveraging blockchain technology and innovative web development, we ensure transparency, efficiency, and security in every transaction. With KryptoJobs2Go, hiring fintech talent has never been easier or more rewarding.

### *Contact Us*
For inquiries or further information, please contact JahunMoayedzadeh@kryptojobs2go.com. We look forward to assisting you with your fintech hiring needs.

#### *NOTE: This is a not real company and created as an assignment for SMU Fintech Bootcamp  
**File Link:** [Krypto Jobs](krypto_jobs.py)