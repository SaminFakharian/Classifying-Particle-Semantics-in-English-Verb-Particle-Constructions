# Classifying-Particle-Semantics-in-English-Verb-Particle-Constructions
 
Nowadays **Multiword expressions (MWEs)** include a wide range of phenomena such as fixed expressions, idioms, and light verb constructions. MWEs are a key problem for the development of a large scale, linguistically sound natural language processing technology. As verb-particle constructions (VPCs) are a rich source of MWEs in English, many works focused on their compositionality. However, the works in this area do not answer to the question that which meaning of a component word is being used when MWE is compositional.

We decide to address the issue of finding which meaning of a component word is being used in the VPCs by classifying the particle semantics, in this work the particle "up". We develop a feature space for use in our classification of the sense the particle contributed in a VPC. For our feature space we re-implement the particle features from our baseline paper and also we used multiple word embedding methods. Our results show that our features mostly outperform the slot features used by the base paper in our classification task on unseen test VPCs.

Word-level embeddings:
	
	- Word2vec
	- GloVe

Classifiers:
	
	- Linear SVM
	- SVM (radial basis function kernel) 
	- Logistic Regression
	
You can find complete report of the work.