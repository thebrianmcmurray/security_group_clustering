# Security Group Clustering

This code was used to assist in the migration from massive security group membership sprawl to RBAC (Role Based Access Control) in a large company's Active Directory domain. As made apparent using the provided sample data, the organization had a trend of having more unique security groups than users, and a large number of unique combinations of security groups. 

This method uses one-hot dummy encoding and K-Means clustering to find natural patterns within the users, and provide visualizations and metrics to determine the optimal number of groups to use. The Jupyter notebook was written with markup and HTML code to allow it to be exported to a PDF for review with key stakeholders.

Tools used:
- Isolation Forests
- MCA (Multiple Correspondence Analysis)
- K-Means Clustering

Other clustering algorithms were also tested, including: 
- OPTICS
- SpectralClustering
- AffinityPropagation
- DBSCAN
