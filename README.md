# NIFTHool
Repository Nifthool project.

NIFtHool: an Informatics Program for Identification of nifH Proteins using Deep Neural Networks

Atmospheric nitrogen fixation by microorganisms has particular environmental and industrial importance related to the soil fertility increase and productivity, plant support, and derived nutrient webs. The present work proposes developing a new computer program to give a reliable prediction for identifying the nitrogenase enzyme from different Nitrogen-fixing microorganisms. Thus, developing a high precision recognition system based on amino acid sequence reads would provide a promising way to improve the recognition of diazotrophic bacteria. For this purpose, a database obtained from Uniprot was built. Data was formed by a set of 2344 amino acid sequences of the NifH and non-NifH proteins. Subsequently, the feature extraction was developed using embedding layers to obtain matrices of the amino acid chains. Afterward, the data was crossed by an external trainable convolutional layer, which received a uniform matrix and applied convolution using filters to obtain the feature maps of the model. Finally, a Deep Neural Network was used as the primary model to classify the amino acid sequences. These sequences were classified depending on whether they are NifH protein or not. Performance evaluation experiments were carried out, and the results revealed an accuracy of 96.95%, a sensitivity of 97%, and a specificity of 96.5%. Therefore, an amino acid sequence-based feature extraction method that uses a neural network to detect N-fixing organisms is proposed and implemented.

To use the app in AnvilWorks: https://nifthool.anvil.app
