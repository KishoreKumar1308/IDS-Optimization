# IDS-Optimization
Optimizing Intrusion Detection Sytem (IDS) using Meta-Heuristic optimization algorithms

# Overview
IDS deals with identifying and preventing various malicious attacks on computer networks. Traditional IDS systems are rule based, which lack the ability to idenitfy unseen or new threats. This can be overcome using machine learning methods. The problem with using ML methods is that, they suffer from the curse of dimensionality. Meta-Heuristic optimization algorithms can be used for analysing and selecting the relevant and important features required. This will make using ML methods for IDS a feasible technique

# Optimization algorithms used
## Harmony Search
Harmony Search (HS) is a meta-heuristic search algorithm that draws inspiration from the improvisation process of musicians to find harmonious solutions. In recent years, HS has garnered considerable attention due to several advantages it offers. Implementing HS is straightforward, and the algorithm has demonstrated fast convergence to optimal solutions. Moreover, HS is capable of finding sufficiently good solutions within a reasonable computational time. These merits have made the HS algorithm a popular choice for optimizing various engineering problems across different domains.

## Artificial Bee Colony
In the Artificial Bee Colony (ABC) Algorithm, the colony comprises three types of bees: employed bees, onlooker bees, and scout bees. Employed bees are assigned to specific food sources and perform local searches to improve the quality of their associated solutions. Onlooker bees observe the dances performed by employed bees to select promising food sources. Scout bees, initially, discover all the food source positions randomly. During the optimization process, both employed and onlooker bees exploit the nectar of food sources, gradually depleting their resources. As a result, employed bees may become exhausted. In such cases, the employed bee that exploited the exhausted food source transforms into a scout bee and begins searching for new food sources once again. In essence, an employed bee becomes a scout bee when its food source is depleted. In ABC, each food source represents a potential solution to the problem being solved, and the nectar amount associated with a food source represents the quality or fitness of that solution.

# Approach followed

The NSL KDD dataset was used for training and evaluating the model. Three approaches where followed, which involves using HS for feature selection, using ABC for feature selection and combining both the algorithms (HS+ABC) for feature selection. The resulting models were evaluated on the basis of False Positive rate.

# Result

![image](https://github.com/KishoreKumar1308/IDS-Optimization/assets/62205360/2f4920ba-c6b8-4c52-b653-a541299768af)

The proposed system produces very close results to the existing systems, with fewer number of features. Reduced number of features will help in quicker training and updation of model and in detection of the intrusion in a system
