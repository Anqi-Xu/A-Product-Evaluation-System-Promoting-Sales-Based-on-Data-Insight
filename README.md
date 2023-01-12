# Research-on-User-Download-Behavior-based-on-Google-Play-App-Data-

After a series of data processing and modeling, our team finally gets a reputation-based sales plan for microwaves, pacifiers and hair dryers to help Sunshine Company improve its market competitiveness.


First, we do the data-preprocessing, which includes data redundancy processing, word reduction, and index quantification. At the same time, for the convenience of research, we quantify two specific indexes: verified-purchase and vine. Also, in order to achieve the rankings from the text-based reviews, we use TF-IDF (Term Frequency–Inverse Document Frequency) and LSA (Latent Semantic Analysis) methods to deeply mine the customer satisfaction information contained in them and successfully classify the customer reviews.


Second, we build the Product Reputation Analysis Model based on the two dimensions of customer satisfaction and review credibility. When measuring customer satisfaction level, we examine the star ratings and review ratings, and finally determine the CSI (Customer Satisfaction Index). When measuring the credibility of customer reviews, we use AHP(Analytic Hierarchy Process) and TOPSIS(Technique for Order Preference by Similarity to an Ideal Solution ) methods to weigh the various indicators on customers and reviews, which finally yield the RCI (Review Credibility Index). On this basis, we establish the relationship between the CSI and RCI, and respectively obtain the brand’s PRI (Product Reputation Index) of the microwave, pacifier, and hair dryer. Based on the results of this part of the research, we are able to propose to the marketing director of the most attractive features of the product and recommend the most popular product brands.


Third, on the basis of the PRI, in order to explore the relationship between the reputation of different products and changes in time, we combined the ARIMA model in Time Series to fully analyze and reasonably predict the mean of different products. The accuracy of prediction
was improved by establishing a regression model. By analyzing and solving long-term trends and cyclical trends, we successfully established a traditional time series forecasting model with appropriate fitting degrees.


Fourth, Spearman’s rank correlation coefficient is also applied to measure the impact of specific star ratings on customer reviews before and after certain time node by month. At the same time, we find that although there is a certain correlation between product ratings and reviews, the connection is not so close.


Finally, we change the numeral value of the parameter CSI and PRI to examine the sensitivity
of our Product Reputation Analysis Model. The result shows that our model is robust.
