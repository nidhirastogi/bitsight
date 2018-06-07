# bitsight
#### Introduction

Congratulations on making it this far through the hiring process and thank you for considering working with us.

This data processing exercise is a part of the hiring process and we will use it to understand how well you can analyze data and draw conclusions from it. The data set we’re using for this test is a community dataset and similar to those that we typically use in the product.  

Other than the data, the test material is confidential and proprietary information of BitSight, so please don’t post any of the test material online or share them with others.

Good luck!

#### Problem Instructions

1.	This is a timed exercise; however, it is on the honor system. We expect you to spend no more than two to six hours total over the next 72 hours to complete it. No need to rush. We don’t consider how long it takes you to complete the problem so please take the time to check your work thoroughly before submission. If you do not finish within the time allotted, please submit what you have completed and provide an explanation in your email of what work remains to be done. For example, if there other attributes about the data that you otherwise did not have time to assess or analyze, you may state what you had planned on doing. Given the diversity of attributes in the dataset and the minimal amount of time offered, we expect this list to be present.

2.	Your solution will be judged primarily on your ability to assess the dataset, the conclusions you are able to draw from it, and why conclusions you make might be incorrect. We also place heavy emphasis on your ability to communicate the results clearly and in a meaningful way, even if findings are not significant.

3.	You must work independently. You cannot consult with anyone else, although you are free to research or learn about any topics as you would in a standard working environment. If you have any questions about the problem, feel free to reach back out but we may likely advise you to use your best judgement and state your assumptions in the result. 

4.	Your analysis can contain anything you think best conveys your results, which include both representative charts, or may consist of only written statements.

5.	When you have finished, please reply to this email with the contents of your analysis attached. You can send us your results in any form that makes sense to you. If you’ve used a Jupyter Notebook or something similar, exporting as HTML would be preferred. If not, you could send us your results in a written document, preferably exported as HTML or PDF.

#### Dataset

This data for this exercise is a collection of SSL/TLS protocol handshakes and was collected by members of the Censys team at the University of Michigan. The dataset can be found at: 

https://www.dropbox.com/s/czsi730y4evn2hi/20161216-sampled-dataset.gz?dl=0

See below for references to additional contextual information on how this dataset was compiled that might prove useful for your analysis. The number of events contained in this dataset was chosen to allow you to process it on a single computer in a reasonable amount of time.

These events were selected by following the instructions below:

1.	Visit https://scans.io/ and under “Censys · Regularly Scheduled Scans”, choose “443-https-tls-full_ipv4”
2.	Download zgrab-results.json.lz4 for the data collected on “2016-12-16 09:08:09”
3.	Excluding erroneous events, extract the first uncompressed 100,000 events.

You may not be able to reproduce the exact dataset since historical data may not be available.
#### Objective
This exercise is open-ended, and relies upon your ability to receive and process a dataset with only high-level information about it being made available. The analysis serves as a measure of assessing your knowledge of a technical topic, or your capacity to learn and apply it, and be able to use that knowledge to: 

•	Understand the contextual awareness of how this data was likely collected.
•	Identify any likely implicit or explicit biases, if they exist.
•	Aggregate and assess the data in any way that you find is relevant, interesting, important, or noteworthy. This includes anything that would otherwise reveal information about the hosts, reveals trends about configurations of those devices or services, or any notable artifact that may affect the risk profile or attack surface of that device or users interfacing with it.

There will be assumptions you have to make along the way during your assessment, and an important part is stating what these assumptions are, and the effects of what would happen if your assumptions are incorrect.
