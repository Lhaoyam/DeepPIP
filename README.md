# DeepPIP
Proinflammatory peptides (PIPs) are bioactive sequences that can induce inflammatory responses and 
trigger immune cascade reactions in the human body. Because experimental validation of proinflammatory 
activity is costly and labor intensive, there is an urgent need for computational models that can accurately 
identify PIP sequences. In this study, we propose a deep learning framework named DeepPIP for predicting 
proinflammatory peptide activity. This work represents the first application of large protein language models 
for feature encoding of proinflammatory peptides, as well as the first use of deep learning techniques for PIP 
activity prediction. DeepPIP adopts a novel two stage architecture. In the first stage, we design a composite 
feature interaction network composed of a multilayer perceptron (MLP), a bidirectional long short-term 
memory network (BiLSTM), and a multi head attention mechanism to process protein language features 
together with traditional handcrafted features, thereby extracting deep feature representations. In the second 
stage, a Transformer encoder combined with fully connected layers is introduced to construct a Transformer 
based classifier for the final identification of proinflammatory peptides. Compared with existing methods, 
DeepPIP demonstrates substantial performance improvements. On the independent test set ProInTest, 
DeepPIP attains a Matthews correlation coefficient (MCC) of 0.522, an area under the receiver operating 
characteristic curve (AUC) of 0.808, and an accuracy (ACC) of 0.760, corresponding to improvements of 5.6 
percent, 11.2 percent, and 9.4 percent over the current state of the art, respectively. 
