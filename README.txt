# Citation

Englitz, B. (Bernhard), Gerven, M.A.J. van (Marcel), Paul Watkins, Alexander Ivanenko, Kurt Hammerschmidt (2020).
Classifying sex and strain from mouse ultrasonic vocalizations using deep learning [Data set].
http://hdl.handle.net/11633/di.dcn.DSC_620840_0003_891.

# Abstract

Vocalizations are widely used for communication between animals. Mice use a large repertoire of ultrasonic vocalizations (USVs) in different social contexts. During social interaction recognizing the partner's sex is important, however, previous research remained inconclusive whether individual USVs contain this information.
	Using deep neural networks (DNNs) to classify the sex of the emitting mouse from the spectrogram we obtain unprecedented performance (77%, vs. SVM: 56%, Regression: 51%). Performance was even higher (85%) if the DNN could also use each mouse's individual properties during training, which may, however, be of limited practical value. Splitting estimation into two DNNs, spectrogram-to-features and features-to-sex (60%) failed to reach single-step performance. Extending the features by each USVs spectral line, frequency and time marginal in a semi-convolutional DNN resulted in a performance mid-way (64%). Analyzing the network structure suggests an increase in sparsity of activation and correlation with sex, specifically in the fully-connected layers. A detailed analysis of the USV structure, reveals a subset of male vocalizations characterized by a few acoustic features, while the majority of sex differences appear to rely on a complex combination of many features. The same network architecture was also able to achieve above-chance classification for cortexless mice, which were considered indistinguishable before.
	In summary, spectrotemporal differences between male and female USVs allow at least their partial classification, which enables sexual recognition between mice and automated attribution of USVs during analysis of social interactions.

# Background information

You can find more information, including relevant publications pertaining to this dataset on the collection overview page at http://hdl.handle.net/11633/di.dcn.DSC_620840_0003_891.

A complete list of files that are part of this dataset can be found in the file MANIFEST.txt, including a SHA256 hash for each file to allow verification of correct data transfer.

# Restrictions on data access and reuse 

The access to and use of this dataset is only allowed under the conditions listed in the data use agreement, as detailed in the file LICENSE.txt. 

Neither the Donders Institute or Radboud University, nor the researchers that provide this dataset should be included as an author of publications or presentations if this authorship would be based solely on the use of this data. 

However, we ask you to acknowledge the use of the data and data derived from the data when publicly presenting any results or algorithms that benefitted from their use:

    1) Papers, book chapters, books, posters, oral presentations, and all other presentations of results derived from the data should acknowledge the origin of the data as follows: "Data were provided (in part) by the Donders Institute for Brain, Cognition and Behaviour, Radboud University Nijmegen".
    2) Authors of publications or presentations using the data should cite relevant publications describing the methods developed and used by the Donders Institute to acquire and process the data. The specific publications that are appropriate to cite in any given study will depend on what the data were used for and for what purposes. When applicable, a list of publications will be specified on the collection overview page.
