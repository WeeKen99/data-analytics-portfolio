# Big Data Management at PayPal: A Case Study

**Course:** Big Data Management, Universiti Malaya (2025)  
**Type:** Group research paper (4 co-authors, equal contribution)  
**Focus:** Big data strategy, architecture and governance in fintech

## Summary

PayPal processes **25 billion payment transactions a year** for **more than 430 million active accounts** in over 200 markets. It generates more than 20 TB of log data every day. This paper looks at how PayPal manages big data to support long-term strategy, fraud prevention and competitive advantage.

## What the paper covers

### 1. The 10 V's of big data, applied to PayPal
The paper goes beyond the usual seven characteristics (volume, variety, velocity, veracity, variability, visualisation, value) and adds **validity, volatility and vulnerability**. It argues that they are connected parts of one picture rather than separate properties. For example:
- **Velocity:** real-time payment verification across currencies, with 36,987 transactions per minute (Q3 2021)
- **Veracity and value:** a transaction loss rate of only **0.09%**, which shows how accurate data supports fraud control
- **Volatility:** automated retention policies for about 3 PB of log data per day

### 2. The six phases of big data at PayPal
| Phase | How PayPal does it |
|---|---|
| Generation | Transactions, login activity, device and IP data, geolocation, currency volumes |
| Acquisition | KYC verification through third parties; Hadoop cleaning of semi-structured logs |
| Storage | Migration from on-premises data centres to **Google Cloud** with Deloitte (20% of core infrastructure), plus AWS and Azure |
| Analysis | Fraud models that evaluate about 300 variables per event; personalised marketing |
| Visualisation | Tableau dashboards; the merchant-facing Business Insights Dashboard |
| Decision-making | Real-time creditworthiness scoring; less manual oversight |

### 3. Why PayPal needs big data software
- **Fraud detection** with Hadoop, Spark and a three-tier graph platform (real-time, interactive and analytics graphs)
- **Risk management** through predictive analytics on more than 1 billion transactions a month
- **Scalability**, with Hadoop and HBase connected to traditional databases

### 4. Key obstacles and solutions
| Challenge | Solution |
|---|---|
| Data growing about 32% a year, putting pressure on infrastructure | **Aerospike Hybrid Memory Architecture** (SSD + Intel Optane) for low-cost real-time fraud SLAs; **Google Cloud Dataflow** for streaming analytics |
| Data quality and governance across isolated systems | Validity checks, standardisation rules, and **data mesh** principles (data owned by domain teams) |
| Shortage of skilled professionals | PayPal University, guilds and hackathons; declarative tools such as **Feast** and Dataflow |

## Takeaway

Big data is a **foundation of PayPal's strategy**, not just a support function. Moving to cloud-native streaming, real-time fraud analytics and a data-mesh governance model has improved PayPal's security, efficiency and speed of decision-making. Investment in people has been as important as the technology.

## Skills demonstrated

Technical research and synthesis · big data architecture (Hadoop, Spark, HBase, Aerospike, GCP Dataflow) · data governance · academic writing (APA referencing)
