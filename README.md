# Recommendation_Systems

Recommendation systems are used to recommend products or service to people based on their relevance. Their goal is to match the users (consumers) with the right items (products or services). There are different types of recommendation systems [1-2]:
- Rule-Based personalization systems
- Content-based filtering systems: “If you liked this item, you might also like …”
- **Collaborative filtering systems:** **Item-Item Collaborative Filtering** (“Customers who liked this item also liked …”), **User-Item Collaborative Filtering** (“Customers who are similar to you also liked …”).Different metrics are used to calculate the similarities between item or user as **Cosine similarity, Mean Squared Difference similarity, Pearson correlation coefficient** etc.

The projects of this repository are based more on the latter two types of recommendation systems. The goal of the main projects in this repository is to recommend:
- **Song:** using **Million Song Dataset** and can be found [here](http://millionsongdataset.com/tasteprofile/).
- **Movies:** using **MovieLens Dataset** from GroupLens Research. The dataset can be found [here](https://grouplens.org/datasets/movielens/).
- **Products:** using **Amazon Reviews data** that can be found [here](http://jmcauley.ucsd.edu/data/amazon/).
- **Restaurant:** using zomata dataset.
- etc.


# References
- [1] Data Mining for Web Personalization, Bamshad Mobasher, from P. Brusilovsky, A. Kobsa, and W. Nejdl (Eds.): The Adaptive Web, LNCS 4321, pp. 90–135, 2007
- [2] How to Build a Recommender System by Martin Kihn, [link](https://blogs.gartner.com/martin-kihn/how-to-build-a-recommender-system-in-python/).
