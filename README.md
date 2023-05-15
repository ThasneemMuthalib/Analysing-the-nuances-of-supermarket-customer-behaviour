# Analysing-the-nuances-of-supermarket-customer-behaviour
Analyzing the nuances of supermarket customer behaviour for  enhanced retail marketing strategies: A case study on customer purchases within Colombo area

## Abstract
Merchants to create and implement efficient marketing strategies that can boost sales and customer loyalty, it is essential to analyze the subtleties of customer behavior. Businesses can customize their marketing efforts to match their customers' demands and offer better shopping experiences by learning about their consumers' spending habits, buying tendencies, and preferences. This research aims to explore the customer behavior in supermarkets which could create and implement efficient marketing strategies that can boost sales and customer loyalty. Thus, the study was conducted on two paths to get more insights of customers. 

Association rules were mined to figure out the most related items that has been sold out together, which resulted in 3508 rules using Fp-tree method, where products along with their brands were included for future promotional discounts with a threshold support of 0.0007 and only product categories were considered for display rack arrangements using Apriori algorithm resulted in 10 rules having Beverages, Biscuits, Snacks, Confectionaries and Personal care products with a minimum support of 0.05. As the second objective, consumer segmentation was performed to identify types of customers on 131 households, which resulted in two unique groups ‘Premium customers’ and ‘Standard customers”, who are likely to spend three and half times lesser than the Premium customers. These results were obtained using Hierarchical clustering method with average linkage cosine distance measure, with the best average silhouette score of 0.622. Another five optimal groups were also figured out using Latent Dirichlet allocation with regard to the products they bought. They are, ‘Balanced lifestyle seekers’, ‘Balanced diet consumers’, ‘Food explorers’, ‘Indulgence seekers’, and ‘Whole-food consumers’. 

While both these objectives are helpful to the shop owners and suppliers, a predictive model was built to help the customers. As the third objective, a customer can predict their next invoice amount, if they know the visiting supermarket, buying products and visiting day beforehand using a mixed Random Forest model, which obtained an R squared value of 81.28 percent and 0.4326 RMSE value.


![methodology drawio (3)](https://user-images.githubusercontent.com/86557599/231429786-a85de3fc-71ef-4e6f-b75b-cfabd9fb1e81.png)

