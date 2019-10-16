# Mini-2 Report

## Introduction to the topic

Unsupervised learning is a type of self-organized Hebbian learning that helps find previously unknown patterns in data set without pre-existing labels. It is also known as self-organization and allows modeling probability densities of given inputs. It is one of the main three categories of machine learning, along with supervised and reinforcement learning.

## Summary of references

- A. Hadid, O. Kouropteva and M. Pietikainen, "Unsupervised learning using locally linear embedding: experiments with face pose analysis," Object recognition supported by user interaction for service robots, Quebec City, Quebec, Canada, 2002, pp. 111-114 vol.1.  
This paper considers a recently proposed method for unsupervised learning and dimensionality reduction, locally linear embedding (LLE). LLE computes a compact representation of high-dimensional data combining the major advantages of linear methods (computational efficiency, global optimality, and flexible asymptotic convergence guarantees) with the advantages of non-linear approaches (flexibility to learn a broad class on non-linear manifolds). We assess the performance of the LLE algorithm on real-world data (face images in different poses) and compare the results with those obtained with two different approaches (PCA and SOM). Extensions to the original LLE algorithm are proposed and applied to the problem of pose estimation.

- Ghahramani Z. (2004) Unsupervised Learning. In: Bousquet O., von Luxburg U., Rätsch G. (eds) Advanced Lectures on Machine Learning. ML 2003. Lecture Notes in Computer Science, vol 3176. Springer, Berlin, Heidelberg.  
This paper give a tutorial and overview of the field of unsupervised learning from the perspective of statistical modeling. Unsupervised learning can be motivated from information theoretic and Bayesian principles. We briefly review basic models in unsupervised learning, including factor analysis, PCA, mixtures of Gaussians, ICA, hidden Markov models, state-space models, and many variants and extensions. We derive the EM algorithm and give an overview of fundamental concepts in graphical models, and inference algorithms on graphs. This is followed by a quick tour of approximate Bayesian inference, including Markov chain Monte Carlo (MCMC), Laplace approximation, BIC, variational approximations, and expectation propagation (EP).

## Pros and cons

### Pros:
- Less complexity in comparison with supervised learning. Unlike in supervised algorithms, in unsupervised learning, no one is required to understand and then to label the data inputs. This makes unsupervised learning less complex and explains why many people prefer unsupervised techniques.
- Takes place in real time such that all the input data to be analyzed and labeled in the presence of learners. This helps them to understand very well different models of learning and sorting of raw data.
- It is often easier to get unlabeled data — from a computer than labeled data, which need person intervention. This is also a key difference between supervised and unsupervised learning.

### Cons:
- You cannot get very specific about the definition of the data sorting and the output. This is because the data used in unsupervised learning is labeled and not known. It is a job of the machine to label and group the raw data before determining the hidden patterns.
- Less accuracy of the results. This is also because the input data is not known and not labeled by people in advance, which means that the machine will need to do this alone.
- The results of the analysis cannot be ascertained. There is no prior knowledge in the unsupervised method of machine learning. Additionally, the numbers of classes are also not known. It leads to the inability to ascertain the results generated by the analysis.


## Recommendations for a person who want to develop or use such systems

Unsupervised machine learning purports to uncover previously unknown patterns in data, but most of the time these patterns are poor approximations of what supervised machine learning can achieve. Additionally, since you do not know what the outcomes should be, there is no way to determine how accurate they are, making supervised machine learning more applicable to real-world problems.

The best time to use unsupervised machine learning is when you do not have data on desired outcomes, such as determining a target market for an entirely new product that your business has never sold before. However, if you are trying to get a better understanding of your existing consumer base, supervised learning is the optimal technique.

The patterns you uncover with unsupervised machine learning methods may also come in handy when implementing supervised machine learning methods later on. For example, you might use an unsupervised technique to perform cluster analysis on the data, then use the cluster to which each row belongs as an extra feature in the supervised learning model (see semi-supervised machine learning). Another example is a fraud detection model that uses anomaly detection scores as an extra feature.

## Conclusions

Unsupervised learning is important for understanding the variation and grouping structure of a set of unlabeled data,
and can be a useful pre-processor for supervised learning. It is intrinsically more difficult than supervised learning
because there is no gold standard (like an outcome variable) and no single objective (like test set accuracy). It is an active field of research, with many recently developed tools such as self-organizing maps, independent components analysis and spectral clustering.

