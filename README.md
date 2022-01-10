# MLMF-Multi-Label-Learning-with-Missing-Features-
<H2>Multi-Label Learning with Missing Features (IJCNN'21)</H2>
<P>
Multi-label learning deals with the problem that each example is associated with multiple class labels simultaneously. 
Existing multi-label learning approaches all assume the feature space is completed and construct classification models 
using examples with sufficient feature information. However, in real-world applications, it is difficult to get a fully 
completed feature matrix, that is, only partial feature information of each example can be obtained. In this paper, we 
formalize this problem as multi-label learning with missing features. To tackle this problem, we learn a feature correlation 
matrix and apply it to obtain a new supplementary feature matrix, which has richer feature information than the original 
missing feature matrix. After that, to improve the performance of multi-label classification, we constrain feature correlation 
on coefficient matrix by assuming that if two features are strongly correlated, the similarity between their corresponding 
parameter vector will be large. Besides, we also constrain label correlation on output of labels to capture more sufficient 
relationships between different labels. Extensive experiments show a competitive performance of our method against other 
state-of the-art multi-label learning approaches.
</P>

This work has been published in IJCNN’21:
<H2>References</H2>
<P>Junlong Li, Peipei Li, Yizhang Zou, and Xuegang Hu. Multi-Label Learning with Missing Features. In: Proceedings of IJCNN’21, pp: 1-8.
<P>

<H2>Source codes</H2>
Please refer to the following github website for more details:
https://github.com/SaltedPerson/MLMF


