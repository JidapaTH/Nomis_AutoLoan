# AutoLoan
Currently, only 22% of e-Car’s loan applicants accept a loan offer from e-Car. This is below the industry standard. We attempt to employ different statistical methods to help the company maximize profits by 1) increasing the number of loan applicants that accept an auto loan offer once offered from the incredibly low 22%., 2) identifying the maximum loan interest rate that can be offered to customers who have accepted the auto loan offer.


<p align="center"> <img src="https://github.com/JidapaTH/Nomis_AutoLoan/blob/master/model.jpg"  width="65%" height="65%" ></p>
<p align="center"> Final Model </p>

We ran a K-Means Clustering Analysis to reduce the noise in the data and try to gain as much insight as possible from the statistics. We identified 9 key user clusters, i.e. user groupings, and used these separately to inform our analyses and recommendations. Furthermore, we trained 9 specific Decision Tree models for each of these clusters, and distilled further insight from the customer’s decision making trends. Our goal was to focus on determining which users were higher prone to reject e-Car’s loan offers, and address them with customized APR offerings. For the purpose of this written report, we focused our analysis on the 3 most significant clusters. The rest of the results are available on the complete Python notebook.

<br /> <br /> 

<p align="center"> <img src="https://github.com/JidapaTH/Nomis_AutoLoan/blob/master/cluster.png"  width="80%" height="80%" ></p>
<p align="center">The distribution of APR for each customer segments grouped by outcomes (0 = reject, 1 = accept) </p>

<br /> <br /> 

<p align="center"><img src="https://github.com/JidapaTH/Nomis_AutoLoan/blob/master/clustercha.png"  width="80%" height="80%" ></p>
<p align="center">The characteristic of each cluster </p>

<br /> <br /> 

<p align="center"> <img src="https://github.com/JidapaTH/Nomis_AutoLoan/blob/master/dtree.png"  width="80%" height="80%" ></p>
<p align="center">Decision trees from cluster 0r </p>

Finally, the results our team found serve to highlight many of the key areas where e-Car is missing on potential customers. Our clustering model is particularly useful in segmenting the population into different groups with ranges of common features. 
Conducting our analyzing on a class-by-class basis helps us identify the driving factors in the user’s decision of accepting c.f. rejecting a loan offer. Furthermore, after our analysis we can make a series of recommendations to e-Car that will help the company capture a higher proportion of potential customers that are utilizing e-Car’s online platform:
1. e-Car can utilize the clustering model provided to better address their client base and seek to improve their loan customization process.
2. We notice a substantial room for improvement in terms of existing customer segments that have not been fully exploited. High proportions of the individual cluster distributions are not accepting the current loan offerings by e-Car. 
3. A couple of clusters show margin for higher APR pricing experiments. This would enable e-Car to increase profit on the same loans, while ensuring to keep most of the customers. This resilience trait is key in order to extract higher profits from the existing customer base.
4. That said, most of the remaining user clusters are in need of lower APR offers in order for e-Car to capture a greater proportion of the addressable market
5. e-Car can now utilize our user classes and quantify the sensitivity of different groups to ensure that their marketing and investment efforts are only directed to customers that really have upside potential. 




