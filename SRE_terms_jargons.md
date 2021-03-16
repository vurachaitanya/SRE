#### SRE Terms & Jargons:
-	**SLI :** Service level indicator – the parameters by which a product or service are measured. A number indicating how reliable a product or service is
-	**SLO:** Service level objectives – Setting SLO enables SREs to define objectives and measures for reliability. An agreement with product stake holders on how reliable a product is
-	**SLA :** Service level agreement – The agreement with the customer on the level of availability of the product. An agreement with the customer on how reliable a product or service will be
-	**Blameless Postmortems:** Blamelessness allows engineers to clearly identify where issues lie and ensure the same problem doesn’t happen twice. 
-	**Incident Management:** SREs track all incidents to monitor for progress and higher reliability. 
-	**Automation :** automation is the use of software to create repeatable processes that don’t require human intervention.
-	**Tooling :** Tooling is the technique of creating or acquiring the methodologies, processes and software to reach a goal. 
-	**Product :** Software released to the customer with interactions on its use.
-	**Service:** Software that facilitates outcomes for the customer.
-	**Deployment :** The process of activating a product.
-	**Disaster Recovery :** The plan that enables system to recover from unexpected events. 
-	**Benchmarks :** a point of reference in which things can be compared. 
-	**Metrics:** the result of the measurements taken.
-	**Monitoring:** the act of observing a product for anomalies.
-	**MTBF – Mean time between Failures:** The amount of time between failures.
-	**MTTR – Mean time to repair :** The amount of time it takes to repair a service or product after a failure. 

![SRE Overlap]( https://github.com/vurachaitanya/SRE/blob/main/images/SRE%20Overlaps.JPG)

![SRE depends on]( https://github.com/vurachaitanya/SRE/blob/main/images/SRE%20Terms%20depends.JPG)

### SLI influence SLOs, which determines the SLA’s.


#### SLI (Service Level Indicators):
-	A numerical value : SLIs should be a numerical values such as percentage.
-	What to measure: SLIs can be metrics on latency, throughput, availability and error rate.
-	Measured over time: Metrics are collected over a specified amount of time, such as one year.
-	From the Basis of SLO: SLI from the basis of SLO


#### SLO (Service level objective):
-	Indicates Reliability Goals: A level of availability that acceptable.
-	Agreed upon with product Owners: SLOs are objectives agreed upon by the stake holders of the product. 
-	Measured over time: Metrics are collected over a specified amount of time, such as one year.
-	From the basis of SLAs: SLOs form the basis of SLAs.


#### SLA (Service Level Agreement):
-	Indicates acceptable level of availability : The SLA states the level of availability acceptable to the product owners and customers. 
-	Measured over time: Metrics are collected over a specified amount of time, such as one year.
-	Should be more relaxed than SLOs: SLAs should be more relaxed than SLOs as to leave a buffer for failure before the SLA kicks in.
-	A contract between with the customers: SLAs are official contracts with the customer that state the guaranteed availability and the consequences if isn’t met. 
